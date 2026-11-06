+++
summary = "发送 ICMP Echo 请求，测试网络连通性。"
+++
---

## 用途

发送 ICMP Echo 请求，测试网络连通性。

## 基本语法

```powershell
Test-Connection [-TargetName] 主机 [选项]
```

## 常用参数

- `-Count`：指定发送次数。
- `-Quiet`：只返回布尔结果。
- `-IPv4` / `-IPv6`：指定 IP 协议版本。
- `-TimeoutSeconds`：设置超时时间（版本支持情况不同）。

## 常用示例

```powershell
Test-Connection example.com -Count 4
Test-Connection 192.168.1.1 -Quiet
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Test-Connection -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/test-connection/)。
