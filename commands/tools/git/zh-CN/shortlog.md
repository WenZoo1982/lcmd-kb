+++
summary = "按作者汇总提交记录。"
+++
---

## 用途

快速查看项目贡献者及其提交数量、提交说明。

## 基本语法

```bash
git shortlog
```

## 常用参数

- `-s`：只显示提交数量和作者。
- `-n`：按提交数量排序。
- `-e`：同时显示邮箱。

## 常用示例

```bash
git shortlog -sn
git shortlog -sne
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-shortlog)。
