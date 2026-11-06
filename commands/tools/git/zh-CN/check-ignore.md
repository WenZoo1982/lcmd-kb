+++
summary = "检查文件是否被 .gitignore 规则忽略。"
+++
---

## 用途

文件没有出现在 Git 状态中时，用它查明是哪条忽略规则生效。

## 基本语法

```bash
git check-ignore -v <文件>
```

## 常用参数

- `-v`：显示匹配的规则和来源文件。
- `-n`：显示未匹配规则的检查结果。

## 常用示例

```bash
git check-ignore -v build/output.tmp
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-check-ignore)。
