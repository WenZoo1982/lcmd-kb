+++
summary = "删除文件或目录；PowerShell 使用 Remove-Item，并说明 CMD del 的差异。"
+++
---

## 用途

删除文件或目录。Windows PowerShell 5.1 中，`del` 是 `Remove-Item` 的别名。

## 基本语法

```powershell
del [-Path] 路径 [参数]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 删除文件 | `del .\old.txt` | 删除指定文件 |
| 删除多个文件 | `del .\*.tmp` | 删除匹配的文件 |
| 删除目录及内容 | `del .\Temp -Recurse` | 递归删除目录 |
| 强制删除 | `del .\old.txt -Force` | 尝试删除只读或隐藏项 |
| 预览删除 | `del .\Temp -Recurse -WhatIf` | 不实际删除，先显示操作 |

## 常用示例

```powershell
del .\*.log
del .\Temp -Recurse -WhatIf
```

## 必要注意事项

删除操作可能无法撤销。建议先使用 `-WhatIf` 预览，再执行实际删除。

CMD 的 `del` 使用 `/p`、`/f`、`/s`、`/q` 等参数；PowerShell 使用 `-Force`、`-Recurse`、`-Confirm` 等参数，两者不可混用。

PowerShell 完整语法：`Get-Help Remove-Item -Full`。