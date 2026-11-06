+++
summary = "临时收起尚未提交的改动。"
+++
---

## 用途

需要临时切换分支或处理其他任务，又不想马上提交当前改动时使用。

## 基本语法

```bash
git stash
git stash pop
```

## 常用参数

- `-u`：同时收起未跟踪文件。
- `list`：查看暂存记录。
- `pop`：恢复并删除最近记录。
- `apply`：恢复但保留记录。

## 常用示例

```bash
git stash -u
git stash list
git stash pop
git stash apply stash@{0}
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-stash)。
