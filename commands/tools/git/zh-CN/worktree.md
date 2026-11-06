+++
summary = "在同一个仓库中创建多个工作目录。"
+++
---

## 用途

需要同时处理多个分支，又不想反复切换当前目录时使用。

## 基本语法

```bash
git worktree add <目录> <分支>
git worktree list
```

## 常用参数

- `add -b`：创建新分支并建立工作目录。
- `list`：查看所有工作目录。
- `remove`：移除工作目录。
- `prune`：清理失效记录。

## 常用示例

```bash
git worktree add ../project-hotfix hotfix
git worktree list
git worktree remove ../project-hotfix
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-worktree)。
