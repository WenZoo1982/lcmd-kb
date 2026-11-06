+++
summary = "用指定内容创建或替换文件内容。"
+++
---

## 用途

用指定内容创建或替换文件内容。

## 基本语法

```powershell
Set-Content [-Path] 路径 [-Value] 内容 [选项]
```

## 常用参数

- `-Value`：写入内容。
- `-Encoding`：指定编码。
- `-NoNewline`：不在输出末尾添加换行。
- `-Force`：覆盖受限制的项（适用时）。

## 常用示例

```powershell
Set-Content .\status.txt 'Ready'
Set-Content .\data.txt -Value '你好' -Encoding utf8
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Set-Content -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-content/)。
