+++
summary = "查看远程仓库的分支和标签引用。"
+++
---

## 用途

不克隆仓库，也能快速确认远程是否存在某个分支或标签。

## 基本语法

```bash
git ls-remote <仓库地址>
```

## 常用参数

- `--heads`：只显示分支。
- `--tags`：只显示标签。

## 常用示例

```bash
git ls-remote --heads origin
git ls-remote --tags origin
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-ls-remote)。
