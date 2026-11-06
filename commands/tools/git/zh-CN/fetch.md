+++
summary = "从远程仓库获取更新，但不合并到当前分支。"
+++
---

## 用途

先查看远程有什么新提交，再决定是否合并或变基；比直接 pull 更可控。

## 基本语法

```bash
git fetch <远程仓库>
git fetch --all
```

## 常用参数

- `--all`：获取所有远程仓库。
- `--prune`：清理远程已删除的跟踪分支。
- `--tags`：同时获取标签。

## 常用示例

```bash
git fetch origin
git fetch --all --prune
git log --oneline HEAD..origin/main
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-fetch)。
