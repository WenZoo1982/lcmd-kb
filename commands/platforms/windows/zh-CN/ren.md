+++
summary = "重命名文件或目录；PowerShell 使用 Rename-Item，并说明 CMD ren 的差异。"
+++
---

## 用途

重命名文件或目录。Windows PowerShell 5.1 中，`ren` 是 `Rename-Item` 的别名。

## 基本语法

```powershell
ren [-Path] 原名称 [-NewName] 新名称 [参数]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 重命名文件 | `ren .\old.txt new.txt` | 将文件改为新名称 |
| 重命名目录 | `ren .\OldFolder NewFolder` | 修改目录名称 |
| 使用完整路径 | `ren C:\Temp\a.txt b.txt` | 在原目录中重命名 |
| 预览操作 | `ren .\old.txt new.txt -WhatIf` | 预览重命名操作 |

## 常用示例

```powershell
ren .\report-old.txt report.txt
ren .\OldFolder NewFolder -WhatIf
```

## 必要注意事项

`-NewName` 通常填写新名称，不要把它当作目标目录路径；需要移动文件时应使用 `Move-Item`。

CMD 的 `ren` 使用 `ren 原名称 新名称` 形式，并支持不同的通配符规则。不要直接套用 CMD 的通配符用法。

PowerShell 完整语法：`Get-Help Rename-Item -Full`。