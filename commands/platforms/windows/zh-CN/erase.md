+++
summary = "删除文件或目录；PowerShell 中 erase 是 Remove-Item 的别名。"
+++
---

## 用途

删除文件或目录。Windows PowerShell 5.1 中，`erase` 与 `del` 一样，都是 `Remove-Item` 的别名。

## 基本语法

```powershell
erase [-Path] 路径 [参数]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 删除文件 | `erase .\old.txt` | 删除指定文件 |
| 删除匹配文件 | `erase .\*.tmp` | 删除匹配的文件 |
| 递归删除目录 | `erase .\Temp -Recurse` | 删除目录及其内容 |
| 强制删除 | `erase .\old.txt -Force` | 尝试删除只读或隐藏项 |
| 预览操作 | `erase .\Temp -Recurse -WhatIf` | 预览而不执行 |

## 常用示例

```powershell
erase .\cache\*.tmp
erase .\old-folder -Recurse -WhatIf
```

## 必要注意事项

PowerShell 中 `erase` 与 `del` 功能相同，均调用 `Remove-Item`。删除前建议使用 `-WhatIf` 预览。

CMD 的 `erase` 是 `del` 的同义内部命令，使用斜杠参数；不要将 CMD 参数直接用于 PowerShell。

PowerShell 完整语法：`Get-Help Remove-Item -Full`。