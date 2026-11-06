+++
summary = "列出文件、目录或注册表项。"
+++
---

## 用途

列出文件、目录或注册表项。

## 基本语法

```powershell
Get-ChildItem [[-Path] 路径] [选项]
```

## 常用参数

- `-Force`：包括隐藏项和系统项。
- `-Recurse`：递归遍历子目录。
- `-Filter`：在提供程序端筛选。
- `-File` / `-Directory`：只显示文件或目录。
- `-Name`：只输出名称。

## 常用示例

```powershell
Get-ChildItem C:\Windows
Get-ChildItem . -File
Get-ChildItem . -Filter *.log -Recurse
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-ChildItem -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-childitem/)。
