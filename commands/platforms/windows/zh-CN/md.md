+++
summary = "创建目录；PowerShell 中 md 是 mkdir 函数的别名。"
+++
---

## 用途

创建目录。Windows PowerShell 5.1 中，`md` 是 `mkdir` 函数的别名，最终使用 `New-Item` 创建目录。

## 基本语法

```powershell
md 路径
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 创建目录 | `md .\Logs` | 在当前目录创建 Logs |
| 创建多级目录 | `md .\Data\Archive -Force` | 创建目录路径 |
| 指定完整路径 | `md D:\Backup\Logs` | 在指定位置创建目录 |

## 常用示例

```powershell
md .\Logs
md D:\Backup\Daily -Force
```

## 必要注意事项

PowerShell 中 `md` 是 `mkdir` 的别名，不是 CMD 命令解析器。CMD 的 `md` 与 PowerShell 的目录创建命令用途相近，但参数规则并不完全相同。

PowerShell 完整语法：`Get-Help New-Item -Full`。