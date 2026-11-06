+++
summary = "解析分支、标签或提交表达式。"
+++
---

## 用途

在脚本中获取仓库根目录、当前提交号或规范化路径。

## 基本语法

```bash
git rev-parse <表达式>
```

## 常用参数

- `--show-toplevel`：显示仓库根目录。
- `--short HEAD`：显示当前提交短哈希。
- `--abbrev-ref HEAD`：显示当前分支名。

## 常用示例

```bash
git rev-parse --show-toplevel
git rev-parse --short HEAD
git rev-parse --abbrev-ref HEAD
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-rev-parse)。
