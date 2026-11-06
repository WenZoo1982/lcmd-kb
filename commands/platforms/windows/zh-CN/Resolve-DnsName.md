+++
summary = "查询 DNS 记录。"
+++
---

## 用途

查询 DNS 记录。

## 基本语法

```powershell
Resolve-DnsName [-Name] 域名 [选项]
```

## 常用参数

- `-Type`：指定记录类型，如 A、AAAA、MX、TXT。
- `-Server`：指定 DNS 服务器。
- `-DnsOnly`：只使用 DNS 查询。
- `-NoHostsFile`：不检查 Hosts 文件。

## 常用示例

```powershell
Resolve-DnsName example.com
Resolve-DnsName example.com -Type MX
Resolve-DnsName example.com -Server 1.1.1.1
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Resolve-DnsName -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/resolve-dnsname/)。
