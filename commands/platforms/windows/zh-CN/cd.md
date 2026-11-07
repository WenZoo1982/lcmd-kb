+++
summary = "切换当前工作目录；PowerShell 使用 Set-Location，并补充 CMD cd 的差异。"
+++
---

## 用途

切换当前工作目录。Windows PowerShell 5.1 中，`cd` 是 `Set-Location` 的常用别名。

## 基本语法

```powershell
cd [[-Path] 路径]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 查看当前目录 | `pwd` | 显示当前工作目录 |
| 进入指定目录 | `cd C:\Windows` | 切换到指定目录 |
| 返回上级目录 | `cd ..` | 切换到父目录 |
| 返回用户目录 | `cd ~` | 切换到当前用户主目录 |
| 切换盘符 | `cd D:\` | 直接切换到 D 盘路径 |

## 常用示例

```powershell
cd D:\Downloads
cd ..
cd ~
```

## 必要注意事项

CMD 的 `cd /d D:\路径` 可以同时切换驱动器和目录；PowerShell 不使用 `/d`，直接执行 `cd D:\路径` 即可。

PowerShell 完整语法：`Get-Help Set-Location -Full`。