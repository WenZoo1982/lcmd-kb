+++
summary = "按条件筛选管道对象；PowerShell 中 where 是 Where-Object 的别名，注意与 where.exe 区分。"
+++
---

## 用途

按条件筛选管道中的对象。Windows PowerShell 5.1 中，`where` 是 `Where-Object` 的别名。

## 基本语法

```powershell
命令 | where { 条件 }
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 筛选进程 | `Get-Process \| where { $_.CPU -gt 10 }` | 只保留 CPU 时间大于 10 的进程 |
| 筛选服务 | `Get-Service \| where { $_.Status -eq 'Running' }` | 只保留正在运行的服务 |
| 按属性筛选 | `Get-ChildItem \| where { $_.Length -gt 1MB }` | 筛选大于 1 MB 的文件 |

## 常用示例

```powershell
Get-Service | where { $_.Status -eq 'Running' }
Get-ChildItem -File | where { $_.Length -gt 1MB }
```

## 必要注意事项

这是一个容易混淆的名称：PowerShell 中直接输入 `where` 会优先调用 `Where-Object` 别名；Windows 自带的文件定位程序是外部命令 `where.exe`。

如需在 PowerShell 中查找可执行文件，请明确输入 `where.exe notepad.exe`。不要把 CMD 的 `where 文件名` 语法当成 PowerShell 的 `where` 用法。

PowerShell 完整语法：`Get-Help Where-Object -Full`。