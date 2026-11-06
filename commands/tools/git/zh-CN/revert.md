+++
summary = "创建一个新提交，用来抵消指定提交的改动。"
+++
---

## 用途

撤销已经推送或与他人共享的提交时使用，不直接删除原有历史。

## 基本语法

```bash
git revert <提交号>
```

## 常用参数

- `--no-edit`：使用默认提交说明。
- `--no-commit`：只应用反向改动，暂不提交。
- `--abort`：冲突时放弃操作。

## 常用示例

```bash
git revert a1b2c3d
git revert --no-edit HEAD
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-revert)。
