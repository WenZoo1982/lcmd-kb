+++
summary = "查看提交历史。"
+++
---

## 用途

查找以前改了什么、谁提交的，以及提交发生的时间。

## 基本语法

```bash
git log
```

## 常用参数

- `--oneline`：每次提交压缩成一行。
- `--graph`：用字符显示分支合并图。
- `--all`：查看所有分支历史。
- `-n <数量>`：只显示最近几条。

## 常用示例

```bash
git log --oneline -5
git log --oneline --graph --all
git log -- README.md
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-log)。
