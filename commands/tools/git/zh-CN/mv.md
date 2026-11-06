+++
summary = "移动或重命名文件，并更新 Git 跟踪信息。"
+++
---

## 用途

在项目中移动或重命名已被 Git 跟踪的文件。

## 基本语法

```bash
git mv <原路径> <新路径>
```

## 常用参数

- `-f`：允许覆盖目标路径。
- `-k`：跳过会导致错误的文件。

## 常用示例

```bash
git mv old-name.txt docs/new-name.txt
git status
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-mv)。
