+++
summary = "清空当前终端屏幕显示；PowerShell 使用 Clear-Host。"
+++
---

## 用途

清空当前 PowerShell 主机的屏幕显示。Windows PowerShell 5.1 中，`cls` 是 `Clear-Host` 的别名。

## 基本语法

```powershell
cls
```

## 常用参数

`cls` 不需要常用参数。

## 常用示例

```powershell
cls
```

执行后清除当前终端窗口中已经显示的内容，方便继续查看新的输出。

## 必要注意事项

`cls` 只清理终端显示，不会删除命令历史、文件或程序数据。CMD 中也有 `cls` 内部命令，但具体显示行为由终端宿主决定。

PowerShell 完整命令：`Clear-Host`。