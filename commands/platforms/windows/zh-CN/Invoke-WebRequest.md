+++
summary = "发送 HTTP/HTTPS 请求并获取响应内容。"
+++
---

## 用途

发送 HTTP/HTTPS 请求并获取响应内容。

## 基本语法

```powershell
Invoke-WebRequest [-Uri] URI [选项]
```

## 常用参数

- `-Method`：指定 GET、POST、PUT 等方法。
- `-Headers`：设置请求头。
- `-Body`：设置请求正文。
- `-OutFile`：将响应保存到文件。
- `-TimeoutSec`：设置超时。
- `-UseBasicParsing`：Windows PowerShell 5.1 常见参数；PowerShell 7 中已不需要。

## 常用示例

```powershell
Invoke-WebRequest https://example.com
Invoke-WebRequest https://example.com -OutFile .\page.html
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Invoke-WebRequest -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/invoke-webrequest/)。
