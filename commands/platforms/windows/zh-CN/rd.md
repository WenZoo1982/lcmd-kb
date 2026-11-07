+++
summary = "删除文件或目录；PowerShell 中 rd 是 Remove-Item 的别名。"
+++
---

## 用途

删除文件或目录。Windows PowerShell 5.1 中，`rd` 是 `Remove-Item` 的别名。

## 基本语法

```powershell
rd [-Path] 路径 [参数]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 删除空目录 | `rd .\OldFolder` | 删除指定目录 |
| 删除目录及内容 | `rd .\Temp -Recurse` | 递归删除目录 |
| 强制删除 | `rd .\Temp -Recurse -Force` | 尝试强制删除 |
| 预览操作 | `rd .\Temp -Recurse -WhatIf` | 预览删除操作 |

## 常用示例

```powershell
rd .\EmptyFolder
rd .\Temp -Recurse -WhatIf
```

## 必要注意事项

删除目录及其内容可能无法撤销，执行前建议使用 `-WhatIf`。

CMD 的 `rd` 使用 `/s`、`/q` 等参数；PowerShell 使用 `-Recurse`、`-Force` 等参数，不要混用。

PowerShell 完整语法：`Get-Help Remove-Item -Full`。