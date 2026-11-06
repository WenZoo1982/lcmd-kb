+++
summary = "获取远程更新并整合到当前分支。"
+++
---

## 用途

日常同步远程分支更新。它相当于 fetch 后再执行合并或变基。

## 基本语法

```bash
git pull
 git pull <远程仓库> <分支>
```

## 常用参数

- `--rebase`：用变基方式整合更新。
- `--ff-only`：只允许快进，避免自动产生合并提交。
- `--no-rebase`：使用合并方式。

## 常用示例

```bash
git pull
git pull --ff-only origin main
git pull --rebase
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-pull)。
