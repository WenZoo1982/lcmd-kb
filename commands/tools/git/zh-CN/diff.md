+++
summary = "查看文件改动的具体内容。"
+++
---

## 用途

提交前检查自己改了什么，或比较两个版本之间的差异。

## 基本语法

```bash
git diff
git diff --staged
git diff <版本1> <版本2>
```

## 常用参数

- 默认：查看工作区与暂存区的差异。
- `--staged`：查看已暂存、准备提交的差异。
- `--stat`：只看改动统计。
- `-- <文件>`：只比较指定文件。

## 常用示例

```bash
git diff
git diff --staged
git diff --stat
git diff -- README.md
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-diff)。
