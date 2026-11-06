+++
summary = "将对象写入成功输出流，供后续管道处理。"
+++
---

## 用途

将对象写入成功输出流，供后续管道处理。

## 基本语法

```powershell
Write-Output [-InputObject] 对象 [选项]
```

## 常用参数

- `-NoEnumerate`：不展开集合中的元素。

## 常用示例

```powershell
Write-Output 'Hello'
1..3 | ForEach-Object { Write-Output $_ }
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Write-Output -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/write-output/)。
