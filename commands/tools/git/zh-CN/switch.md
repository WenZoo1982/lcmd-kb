+++
summary = "切换到其他分支，或创建并切换新分支。"
+++
---

## 用途

日常分支切换。新建分支时优先使用这个命令，而不是旧式 checkout。

## 基本语法

```bash
git switch <分支>
git switch -c <新分支>
```

## 常用参数

- `-c`：创建并切换到新分支。
- `-`：切换回上一个分支。
- `--detach`：切换到某个提交但不处于分支上。

## 常用示例

```bash
git switch main
git switch -c feature/login
git switch -
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-switch)。
