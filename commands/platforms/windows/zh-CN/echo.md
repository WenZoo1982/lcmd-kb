+++
summary = "向管道输出文本或对象；PowerShell 中 echo 是 Write-Output 的别名。"
+++
---

## 用途

输出文本或对象。Windows PowerShell 5.1 中，`echo` 是 `Write-Output` 的别名。

## 基本语法

```powershell
echo 内容
```

## 常用参数

`echo` 是 `Write-Output` 的别名，常见用法是直接输出内容，也可以将结果传递给管道。

## 常用示例

```powershell
echo "Hello World"
echo "LCMD" | Set-Content .\name.txt
echo "alpha", "beta" | ForEach-Object { $_ }
```

输出文本，也可以将输出交给后续命令处理。

## 必要注意事项

PowerShell 的 `echo` 会向管道输出对象；它不等同于 CMD 中用于控制命令回显状态的 `echo on` 或 `echo off`。在 PowerShell 中输入 `echo off` 只会输出文本 `off`。

PowerShell 完整语法：`Get-Help Write-Output -Full`。