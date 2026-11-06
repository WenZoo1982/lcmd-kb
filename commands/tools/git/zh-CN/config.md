+++
summary = "设置或查看 Git 配置。"
+++
---

## 用途

设置提交者身份、默认分支名称、编辑器等常用选项。

## 基本语法

```bash
git config --<级别> <配置项> <值>
git config --<级别> --list
```

## 常用参数

- `--global`：当前用户所有仓库生效。
- `--local`：只对当前仓库生效。
- `--list`：列出配置。
- `--get`：读取指定配置项。

## 常用示例

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --global --list
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-config)。
