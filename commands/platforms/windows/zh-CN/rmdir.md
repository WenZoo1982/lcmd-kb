+++
summary = "删除目录；PowerShell 中 rmdir 是 Remove-Item 的别名。"
+++
---

## 用途

删除目录或其他文件系统项。Windows PowerShell 5.1 中，`rmdir` 是 `Remove-Item` 的别名。

## 基本语法

```powershell
rmdir [-Path] 路径 [参数]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 删除空目录 | `rmdir .\OldFolder` | 删除指定目录 |
| 删除目录及内容 | `rmdir .\Temp -Recurse` | 递归删除目录 |
| 强制删除 | `rmdir .\Temp -Recurse -Force` | 尝试强制删除 |
| 预览操作 | `rmdir .\Temp -Recurse -WhatIf` | 预览删除操作 |

## 常用示例

```powershell
rmdir .\EmptyFolder
rmdir .\Temp -Recurse -WhatIf
```

## 必要注意事项

PowerShell 中 `rmdir` 与 `rd`、`del` 一样，最终调用 `Remove-Item`。CMD 的 `rmdir /s /q` 参数不能直接用于 PowerShell。

PowerShell 完整语法：`Get-Help Remove-Item -Full`。