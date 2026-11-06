+++
summary = "比较两组提交系列的差异。"
+++
---

## 用途

修改过一轮提交或变基后，检查新旧补丁系列是否发生变化。

## 基本语法

```bash
git range-diff <旧范围> <新范围>
```

## 常用参数

- `--creation-factor=<百分比>`：调整提交匹配的宽松程度。

## 常用示例

```bash
git range-diff main...feature-old main...feature-new
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-range-diff)。
