+++
summary = "将对象转换为 XML 表示。"
+++
---

## 用途

将对象转换为 XML 表示。

## 基本语法

```powershell
对象 | ConvertTo-Xml [选项]
```

## 常用参数

- `-As`：选择 String、Stream 或 Document。
- `-Depth`：指定转换深度。
- `-NoTypeInformation`：省略类型信息。

## 常用示例

```powershell
Get-Process | Select-Object -First 2 Name,Id | ConvertTo-Xml -As String
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help ConvertTo-Xml -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/convertto-xml/)。
