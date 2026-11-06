+++
summary = "生成随机数或从集合中随机选择对象。"
+++
---

## 用途

生成随机数或从集合中随机选择对象。

## 基本语法

```powershell
Get-Random [选项]
```

## 常用参数

- `-Minimum` / `-Maximum`：指定随机数范围。
- `-Count`：返回多个结果。
- `-InputObject`：从指定集合中选择。
- `-SetSeed`：设置随机种子。

## 常用示例

```powershell
Get-Random -Minimum 1 -Maximum 101
Get-ChildItem | Get-Random -Count 3
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-Random -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-random/)。
