+++
summary = "在受 Git 管理的文件中搜索文本。"
+++
---

## 用途

快速查找代码、配置项或某个函数名。

## 基本语法

```bash
git grep <关键词>
```

## 常用参数

- `-n`：显示行号。
- `-i`：忽略大小写。
- `-l`：只显示匹配的文件名。
- `-e`：指定搜索表达式。

## 常用示例

```bash
git grep -n "TODO"
git grep -i "timeout"
git grep "def main" -- '*.py'
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-grep)。
