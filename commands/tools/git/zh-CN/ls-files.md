+++
summary = "列出 Git 索引中的文件。"
+++
---

## 用途

查看哪些文件已被 Git 跟踪，或检查暂存区中的文件列表。

## 基本语法

```bash
git ls-files
```

## 常用参数

- `-m`：显示有修改的跟踪文件。
- `-o`：显示未跟踪文件。
- `-s`：显示索引详细信息。

## 常用示例

```bash
git ls-files
git ls-files -o --exclude-standard
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-ls-files)。
