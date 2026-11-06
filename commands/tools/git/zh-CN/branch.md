+++
summary = "查看、创建、重命名或删除分支。"
+++
---

## 用途

管理项目分支；切换分支建议优先使用 `git switch`。

## 基本语法

```bash
git branch
git branch <新分支>
git branch -d <分支>
```

## 常用参数

- `-a`：查看本地和远程分支。
- `-r`：只看远程分支。
- `-d`：删除已合并的本地分支。
- `-D`：强制删除分支。
- `-m`：重命名当前分支。

## 常用示例

```bash
git branch -a
git branch feature/login
git branch -d feature/login
git branch -m old-name new-name
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-branch)。
