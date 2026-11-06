+++
summary = "列出指定范围内的提交。"
+++
---

## 用途

统计提交数量，或在脚本中获取某个分支范围内的提交列表。

## 基本语法

```bash
git rev-list <范围>
```

## 常用参数

- `--count`：只输出提交数量。
- `--all`：遍历所有引用可达的提交。

## 常用示例

```bash
git rev-list --count HEAD
git rev-list --oneline main..feature
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-rev-list)。
