+++
summary = "扫描并修复受保护的 Windows 系统文件。"
+++
---

## 用途

扫描并修复受保护的 Windows 系统文件。

## 基本语法

```cmd
sfc [/scannow | /verifyonly]
```

## 常用参数

/scannow 立即扫描并尝试修复；/verifyonly 仅验证，不修复。通常需要以管理员身份运行。

## 常用示例

```cmd
sfc /scannow
```

## 使用提示

此命令属于：Windows 系统工具。在 CMD 中运行。部分操作需要管理员权限；执行删除、覆盖或系统维护操作前，请确认目标和影响范围。

## 更多参数

运行 `sfc /?` 查看当前 Windows 版本提供的完整语法和参数。
