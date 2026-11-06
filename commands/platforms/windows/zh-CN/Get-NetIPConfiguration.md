+++
summary = "查看网络适配器的 IP 配置。"
+++
---

## 用途

查看网络适配器的 IP 配置。

## 基本语法

```powershell
Get-NetIPConfiguration [选项]
```

## 常用参数

- `-InterfaceAlias`：按适配器名称筛选。
- `-All`：包含更多适配器信息。
- `-Detailed`：显示详细配置。

## 常用示例

```powershell
Get-NetIPConfiguration
Get-NetIPConfiguration -Detailed
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-NetIPConfiguration -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-netipconfiguration/)。
