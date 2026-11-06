+++
summary = "获取网络接口的 IP 地址配置。"
+++
---

## 用途

获取网络接口的 IP 地址配置。

## 基本语法

```powershell
Get-NetIPAddress [选项]
```

## 常用参数

- `-AddressFamily`：筛选 IPv4 或 IPv6。
- `-InterfaceAlias`：指定网络适配器。
- `-IPAddress`：按地址筛选。

## 常用示例

```powershell
Get-NetIPAddress
Get-NetIPAddress -AddressFamily IPv4
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-NetIPAddress -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-netipaddress/)。
