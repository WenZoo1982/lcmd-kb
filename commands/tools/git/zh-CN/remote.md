+++
summary = "查看和管理远程仓库地址。"
+++
---

## 用途

查看项目连接了哪些远程仓库，或添加、修改远程地址。

## 基本语法

```bash
git remote -v
git remote add <名称> <地址>
```

## 常用参数

- `-v`：显示远程仓库地址。
- `add`：添加远程仓库。
- `set-url`：修改远程地址。
- `remove`：删除远程仓库配置。

## 常用示例

```bash
git remote -v
git remote add origin https://github.com/user/project.git
git remote set-url origin <新地址>
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-remote)。
