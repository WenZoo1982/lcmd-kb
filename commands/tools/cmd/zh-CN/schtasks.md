+++
summary = "创建、查询、运行或管理 Windows 计划任务。"
+++
---

## 用途

创建、查询、运行或管理 Windows 计划任务。

## 基本语法

```cmd
schtasks /操作 [选项]
```

## 常用参数

/query 查询；/create 创建；/run 立即运行；/end 结束；/delete 删除。创建或管理任务可能需要管理员权限。

## 常用示例

```cmd
schtasks /query /fo LIST /v
```

## 使用提示

此命令属于：Windows 系统工具。在 CMD 中运行。部分操作需要管理员权限；执行删除、覆盖或系统维护操作前，请确认目标和影响范围。

## 更多参数

运行 `schtasks /?` 查看当前 Windows 版本提供的完整语法和参数。
