+++
summary = "生成请求他人拉取本地分支的摘要。"
+++
---

## 用途

通过邮件或文字向维护者说明某个分支包含哪些待合并改动。

## 基本语法

```bash
git request-pull <基点> <仓库地址> <分支>
```

## 常用参数

- `<基点>`：对方已有的基础提交。
- `<仓库地址>`：对方可访问的仓库地址。
- `<分支>`：包含待合并提交的分支。

## 常用示例

```bash
git request-pull main https://github.com/user/project.git feature/login
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-request-pull)。
