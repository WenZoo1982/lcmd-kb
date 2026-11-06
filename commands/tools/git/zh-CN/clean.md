+++
summary = "删除未被 Git 跟踪的文件。"
+++
---

## 用途

清理构建产物、临时文件等未纳入版本控制的内容。**执行前先预览，删除后通常无法通过 Git 恢复。**

## 基本语法

```bash
git clean -n
git clean -f
```

## 常用参数

- `-n`：只预览，不删除。
- `-f`：实际删除未跟踪文件。
- `-d`：同时处理未跟踪目录。
- `-x`：连 `.gitignore` 忽略的文件也删除，风险较高。

## 常用示例

```bash
git clean -n
git clean -fd
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-clean)。
