+++
summary = "按属性值对对象分组。"
+++
---

## 用途

按属性值对对象分组。

## 基本语法

```powershell
对象 | Group-Object [-Property] 属性 [选项]
```

## 常用参数

- `-NoElement`：不保留组内原始对象。
- `-AsHashTable`：返回哈希表。
- `-CaseSensitive`：区分大小写分组。

## 常用示例

```powershell
Get-Process | Group-Object ProcessName
Get-ChildItem | Group-Object Extension
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Group-Object -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/group-object/)。
