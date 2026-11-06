+++
summary = "把当前分支的提交重新应用到另一个基点上。"
+++
---

## 用途

让功能分支基于最新主分支继续开发，或整理尚未推送的提交。**已共享的提交不要随意变基。**

## 基本语法

```bash
git rebase <目标分支>
git rebase -i <基点>
```

## 常用参数

- `-i`：交互式整理、合并或修改提交。
- `--continue`：解决冲突后继续。
- `--abort`：放弃变基并恢复原状态。
- `--skip`：跳过当前提交。

## 常用示例

```bash
git fetch origin
git rebase origin/main
git rebase -i HEAD~3
git rebase --abort
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-rebase)。
