+++
summary = "查看提交、标签或其他 Git 对象的详细内容。"
+++
---

## 用途

快速查看某次提交改了什么，或查看标签、文件在某版本中的内容。

## 基本语法

```bash
git show [提交或对象]
```

## 常用参数

- `--stat`：只显示改动统计。
- `--name-only`：只显示改动文件名。
- `--format=oneline`：简化提交信息。

## 常用示例

```bash
git show
git show --stat HEAD
git show HEAD~1:README.md
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-show)。
