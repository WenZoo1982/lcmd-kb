+++
summary = "切换当前工作目录；PowerShell 中 chdir 是 Set-Location 的别名。"
+++
---

## 用途

切换当前工作目录。Windows PowerShell 5.1 中，`chdir` 与 `cd` 一样，都是 `Set-Location` 的别名。

## 基本语法

```powershell
chdir [[-Path] 路径]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 进入指定目录 | `chdir C:\Windows` | 切换到指定目录 |
| 返回上级目录 | `chdir ..` | 切换到父目录 |
| 返回用户目录 | `chdir ~` | 切换到当前用户主目录 |
| 切换到其他盘 | `chdir D:\Downloads` | 切换到目标路径 |

## 常用示例

```powershell
chdir D:\Project
chdir ..
```

## 必要注意事项

PowerShell 中 `chdir` 与 `cd` 功能相同。CMD 的 `cd /d` 参数不适用于 PowerShell；切换盘符时直接指定完整路径。

PowerShell 完整语法：`Get-Help Set-Location -Full`。