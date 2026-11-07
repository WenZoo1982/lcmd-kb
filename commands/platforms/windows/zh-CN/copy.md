+++
summary = "复制文件或目录；PowerShell 使用 Copy-Item，并说明 CMD copy 的参数差异。"
+++
---

## 用途

复制文件或目录。Windows PowerShell 5.1 中，`copy` 是 `Copy-Item` 的别名。

## 基本语法

```powershell
copy [-Path] 源路径 [-Destination] 目标路径 [参数]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 复制文件 | `copy .\a.txt .\Backup\` | 将文件复制到目标目录 |
| 复制并改名 | `copy .\a.txt .\Backup\b.txt` | 复制时指定新文件名 |
| 复制目录 | `copy .\Project .\Backup -Recurse` | 递归复制目录内容 |
| 强制处理 | `copy .\a.txt .\Backup -Force` | 尝试覆盖只读或目标项 |
| 返回结果 | `copy .\a.txt .\Backup -PassThru` | 输出复制后的对象 |

## 常用示例

```powershell
copy .\report.txt D:\Backup\
copy .\Project D:\Backup\Project -Recurse
```

将文件复制到备份目录；复制目录时使用 `-Recurse`。

## 必要注意事项

PowerShell 的 `copy` 实际调用 `Copy-Item`，使用 `-Recurse`、`-Force` 等参数。

CMD 的 `copy` 是内部命令，使用 `/y`、`/v`、`/b` 等参数。两者参数体系不同，不能把 CMD 的 `/y` 直接用于 PowerShell。PowerShell 的 `-Force` 也不等同于 CMD 的所有覆盖选项。

PowerShell 完整语法：`Get-Help Copy-Item -Full`。