+++
summary = "生成终止错误并中断当前执行流程。"
+++
---

## 用途

生成终止错误并中断当前执行流程。

## 基本语法

```powershell
throw [消息或异常对象]
```

## 常用参数

- `throw`：抛出异常或错误消息。
- 结合 `try` / `catch` 捕获和处理异常。

## 常用示例

```powershell
if (-not (Test-Path .\config.json)) { throw '配置文件不存在' }
try { throw 'Something failed' } catch { $_.Exception.Message }
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Throw -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/throw/)。
