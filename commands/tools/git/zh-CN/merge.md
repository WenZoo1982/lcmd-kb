+++
summary = "把另一个分支的改动合并到当前分支。"
+++
---

## 用途

功能分支完成后，将其整合到主分支或目标分支。

## 基本语法

```bash
git merge <分支>
```

## 常用参数

- `--no-ff`：即使可快进也创建合并提交。
- `--abort`：发生冲突且想放弃合并时使用。
- `--continue`：解决冲突后继续合并。

## 常用示例

```bash
git switch main
git merge feature/login
git merge --abort
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-merge)。
