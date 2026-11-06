+++
summary = "切换分支或恢复文件的旧式命令。"
+++
---

## 用途

兼容旧教程和旧脚本。新用法建议使用 `git switch` 切分支、`git restore` 恢复文件。

## 基本语法

```bash
git checkout <分支>
git checkout -b <新分支>
git checkout -- <文件>
```

## 常用参数

- `-b`：创建并切换到新分支。
- `-- <文件>`：用暂存区内容覆盖工作区文件，未提交改动可能丢失。

## 常用示例

```bash
git checkout main
git checkout -b feature/login
git checkout -- README.md
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-checkout)。
