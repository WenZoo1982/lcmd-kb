+++
summary = "创建目录；PowerShell 使用 mkdir 函数创建 Directory 项。"
+++
---

## 用途

创建目录。Windows PowerShell 5.1 中，`mkdir` 是一个函数，可通过 `New-Item` 创建目录。

## 基本语法

```powershell
mkdir 路径
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 创建目录 | `mkdir .\Logs` | 创建 Logs 目录 |
| 创建多级目录 | `mkdir .\Data\Archive -Force` | 创建目录路径 |
| 指定完整路径 | `mkdir D:\Backup\Logs` | 在指定位置创建目录 |

## 常用示例

```powershell
mkdir .\Logs
mkdir D:\Backup\Daily -Force
```

## 必要注意事项

PowerShell 中 `mkdir` 是函数，不是 `New-Item` 的别名；`md` 是它的别名。CMD 的 `mkdir` 与 PowerShell 的参数规则不同。

PowerShell 完整语法：`Get-Help New-Item -Full`。