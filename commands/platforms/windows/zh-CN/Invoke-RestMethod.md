+++
summary = "调用 REST API，并自动解析常见响应格式。"
+++
---

## 用途

调用 REST API，并自动解析常见响应格式。

## 基本语法

```powershell
Invoke-RestMethod [-Uri] URI [选项]
```

## 常用参数

- `-Method`：指定 HTTP 方法。
- `-Headers`：设置请求头。
- `-Body`：传递请求正文。
- `-ContentType`：指定内容类型。
- `-Authentication`：选择认证方式（版本支持情况不同）。

## 常用示例

```powershell
Invoke-RestMethod https://api.github.com
Invoke-RestMethod -Uri https://httpbin.org/post -Method Post -Body @{name='LCMD'}
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Invoke-RestMethod -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/invoke-restmethod/)。
