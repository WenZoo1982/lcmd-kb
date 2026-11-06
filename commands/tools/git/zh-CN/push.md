+++
summary = "把本地提交上传到远程仓库。"
+++
---

## 用途

将本地新提交发布到 GitHub 等远程仓库。

## 基本语法

```bash
git push <远程仓库> <分支>
```

## 常用参数

- `-u`：建立上游跟踪关系，之后通常可直接执行 `git push`。
- `--all`：推送所有本地分支。
- `--tags`：推送所有标签。
- `--force-with-lease`：较安全地强制更新远程引用，仍可能改写远程历史。

## 常用示例

```bash
git push -u origin main
git push
git push origin --tags
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-push)。
