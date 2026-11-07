+++
summary = "显示当前工作目录；PowerShell 使用 Get-Location。"
+++
---

## 用途

显示当前 PowerShell 会话的工作位置。Windows PowerShell 5.1 中，`pwd` 是 `Get-Location` 的别名。

## 基本语法

```powershell
pwd
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 查看当前目录 | `pwd` | 显示当前工作位置 |
| 获取路径字符串 | `(pwd).Path` | 输出当前文件系统路径 |
| 保存当前路径 | `$current = (pwd).Path` | 将路径保存到变量 |

## 常用示例

```powershell
pwd
$current = (pwd).Path
Write-Output $current
```

## 必要注意事项

PowerShell 的 `Get-Location` 返回的是位置对象，不只是普通文本。当前位于文件系统之外的提供程序位置（例如注册表或环境变量驱动器）时，显示内容也不一定是普通磁盘路径。

CMD 中没有同名的标准内部命令；CMD 通常使用 `cd` 查看当前目录。

PowerShell 完整语法：`Get-Help Get-Location -Full`。