+++
summary = "把文件改动放入暂存区。"
+++
---

## 用途

准备下一次提交：告诉 Git 哪些改动需要提交。

## 基本语法

```bash
git add <文件或目录>
git add -p <文件>
```

## 常用参数

- `.`：暂存当前目录下的改动。
- `-A`：暂存整个仓库的新增、修改和删除。
- `-p`：按代码块选择暂存内容。

## 常用示例

```bash
git add README.md
git add .
git add -p src/main.py
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-add)。
