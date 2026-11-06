+++
summary = "把指定提交的改动应用到当前分支。"
+++
---

## 用途

需要把其他分支上的某个修复或功能提交单独移植过来时使用。

## 基本语法

```bash
git cherry-pick <提交号>
```

## 常用参数

- `-n`：应用改动但不自动创建提交。
- `--continue`：解决冲突后继续。
- `--abort`：放弃本次操作。

## 常用示例

```bash
git switch release
git cherry-pick a1b2c3d
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-cherry-pick)。
