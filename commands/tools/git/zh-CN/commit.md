+++
summary = "把暂存区内容保存为一次提交。"
+++
---

## 用途

完成一组改动后创建版本记录。

## 基本语法

```bash
git commit -m "提交说明"
```

## 常用参数

- `-m`：直接填写提交说明。
- `-a`：自动暂存已跟踪文件的修改和删除，不包括新文件。
- `--amend`：修改最近一次提交，可能改写提交历史。

## 常用示例

```bash
git commit -m "修复登录问题"
git commit -am "更新配置"
git commit --amend
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-commit)。
