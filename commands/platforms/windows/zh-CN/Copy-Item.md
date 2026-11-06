+++
summary = "复制文件、目录或其他提供程序项。"
+++
---

## 用途

复制文件、目录或其他提供程序项。

## 基本语法

```powershell
Copy-Item [-Path] 源路径 [-Destination] 目标路径 [选项]
```

## 常用参数

- `-Recurse`：递归复制目录。
- `-Force`：覆盖目标项（适用时）。
- `-Container`：保留目录容器结构。
- `-PassThru`：返回复制后的对象。

## 常用示例

```powershell
Copy-Item .\a.txt .\Backup\
Copy-Item .\Project .\Backup -Recurse
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Copy-Item -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/copy-item/)。
