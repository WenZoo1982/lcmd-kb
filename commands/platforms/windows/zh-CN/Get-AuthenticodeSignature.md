+++
summary = "检查文件的 Authenticode 数字签名状态。"
+++
---

## 用途

检查文件的 Authenticode 数字签名状态。

## 基本语法

```powershell
Get-AuthenticodeSignature [-FilePath] 文件
```

## 常用参数

- `-FilePath`：指定待检查文件。
- 可通过 `Status` 查看签名状态，通过 `SignerCertificate` 查看签名证书。

## 常用示例

```powershell
Get-AuthenticodeSignature .\setup.exe
Get-ChildItem .\*.ps1 | Get-AuthenticodeSignature
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-AuthenticodeSignature -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-authenticodesignature/)。
