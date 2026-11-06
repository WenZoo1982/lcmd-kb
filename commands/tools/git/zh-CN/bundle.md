+++
summary = "把仓库及其历史打包成单个文件。"
+++
---

## 用途

没有网络连接时，用文件传递 Git 仓库或指定分支的历史。

## 基本语法

```bash
git bundle create <文件.bundle> <引用>
git clone <文件.bundle> <目录>
```

## 常用参数

- `create`：创建 bundle 文件。
- `verify`：检查 bundle 是否有效。
- `list-heads`：查看包内包含的分支或标签。

## 常用示例

```bash
git bundle create project.bundle main
git bundle verify project.bundle
git clone project.bundle project-copy
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-bundle)。
