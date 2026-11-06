+++
summary = "启动进程或应用程序。"
+++
---

## 用途

启动进程或应用程序。

## 基本语法

```powershell
Start-Process [-FilePath] 程序 [选项]
```

## 常用参数

- `-ArgumentList`：传递启动参数。
- `-WorkingDirectory`：设置工作目录。
- `-Verb RunAs`：请求以管理员身份运行。
- `-Wait`：等待进程结束。
- `-PassThru`：返回进程对象。

## 常用示例

```powershell
Start-Process notepad.exe
Start-Process powershell.exe -Verb RunAs
Start-Process .\setup.exe -ArgumentList '/quiet' -Wait
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Start-Process -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/start-process/)。
