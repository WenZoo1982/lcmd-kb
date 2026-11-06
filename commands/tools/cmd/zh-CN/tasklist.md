+++
summary = "列出当前运行的进程。"
+++
---

## 用途

列出当前运行的进程。

## 基本语法

```cmd
tasklist [选项]
```

## 常用参数

/fi 按条件筛选；/fo table|list|csv 指定输出格式；/svc 显示每个进程承载的服务。

## 常用示例

```cmd
tasklist /fi "imagename eq notepad.exe"
```

## 使用提示

此命令属于：Windows 系统工具。在 CMD 中运行。部分操作需要管理员权限；执行删除、覆盖或系统维护操作前，请确认目标和影响范围。

## 更多参数

运行 `tasklist /?` 查看当前 Windows 版本提供的完整语法和参数。
