+++
summary = "移动文件或目录；PowerShell 使用 Move-Item，并补充 CMD move 的差异。"
+++
---

## 用途

移动文件或目录，也可在移动时更改名称。Windows PowerShell 5.1 中，`move` 是 `Move-Item` 的别名。

## 基本语法

```powershell
move [-Path] 源路径 [-Destination] 目标路径 [参数]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 移动文件 | `move .\a.txt D:\Backup\` | 将文件移动到目标目录 |
| 移动并改名 | `move .\a.txt .\b.txt` | 移动时更改文件名 |
| 移动目录 | `move .\Project D:\Backup\` | 移动整个目录 |
| 强制处理 | `move .\a.txt D:\Backup\ -Force` | 尝试覆盖目标项 |
| 预览操作 | `move .\a.txt D:\Backup\ -WhatIf` | 只显示计划执行的操作 |

## 常用示例

```powershell
move .\report.txt D:\Backup\
move .\old-name.txt .\new-name.txt
```

## 必要注意事项

PowerShell 的 `move` 调用 `Move-Item`，参数使用 `-Force`、`-WhatIf` 等。

CMD 的 `move` 使用 `/y`、`/-y` 等选项；不要将 CMD 参数直接用于 PowerShell。

PowerShell 完整语法：`Get-Help Move-Item -Full`。