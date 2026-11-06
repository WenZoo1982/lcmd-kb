+++
summary = "比较两组对象并显示差异。"
+++
---

## 用途

比较两组对象并显示差异。

## 基本语法

```powershell
Compare-Object [-ReferenceObject] 参考组 [-DifferenceObject] 比较组 [选项]
```

## 常用参数

- `-Property`：指定比较属性。
- `-IncludeEqual`：同时显示相同项。
- `-PassThru`：返回原始对象。
- `-SyncWindow`：指定比较窗口。

## 常用示例

```powershell
Compare-Object (Get-Content .\old.txt) (Get-Content .\new.txt)
Compare-Object $a $b -Property Name,Version
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Compare-Object -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/compare-object/)。
