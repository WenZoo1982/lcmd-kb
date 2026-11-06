+++
summary = "将管道输出写入文本文件。"
+++
---

## 用途

将管道输出写入文本文件。

## 基本语法

```powershell
对象 | Out-File [-FilePath] 文件 [选项]
```

## 常用参数

- `-Append`：追加到文件。
- `-Encoding`：指定编码。
- `-Width`：设置输出宽度。
- `-NoClobber`：不覆盖已有文件。

## 常用示例

```powershell
Get-Process | Out-File .\processes.txt
Get-Service | Out-File .\services.txt -Append -Encoding utf8
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Out-File -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/out-file/)。
