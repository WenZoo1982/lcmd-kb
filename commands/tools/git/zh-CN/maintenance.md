+++
summary = "执行 Git 仓库维护任务。"
+++
---

## 用途

优化仓库内部数据，通常由 Git 自动维护；大型仓库或维护异常时才需要手动使用。

## 基本语法

```bash
git maintenance run
```

## 常用参数

- `run`：执行维护任务。
- `start`：启用后台定期维护。
- `stop`：停止后台维护。

## 常用示例

```bash
git maintenance run
git maintenance start
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-maintenance)。
