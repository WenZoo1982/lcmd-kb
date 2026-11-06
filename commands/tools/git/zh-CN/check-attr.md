+++
summary = "查看文件匹配到的 Git 属性。"
+++
---

## 用途

排查换行符、文本处理或 diff 规则时，确认某个文件实际使用了哪些属性。

## 基本语法

```bash
git check-attr <属性> -- <文件>
```

## 常用参数

- `--all`：查看该文件的所有属性。
- `-a`：`--all` 的简写。

## 常用示例

```bash
git check-attr --all -- README.md
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-check-attr)。
