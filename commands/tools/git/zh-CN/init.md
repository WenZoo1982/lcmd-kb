+++
summary = "在当前目录创建 Git 仓库。"
+++
---

## 用途

开始用 Git 管理一个尚未进行版本控制的项目。

## 基本语法

```bash
git init
git init <目录>
```

## 常用参数

- `-b <名称>`：指定初始分支名。
- `--bare`：创建裸仓库，通常用于服务器端共享仓库。

## 常用示例

```bash
git init
git init -b main
git init my-project
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-init)。
