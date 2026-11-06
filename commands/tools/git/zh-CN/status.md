+++
summary = "查看工作区和暂存区状态。"
+++
---

## 用途

每次准备提交、切换分支或排查文件状态时，先用它确认当前改动。

## 基本语法

```bash
git status
```

## 常用参数

- `-s`：简短格式。
- `-b`：同时显示当前分支信息。
- `--ignored`：同时显示被忽略的文件。

## 常用示例

```bash
git status
git status -sb
git status --ignored
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-status)。
