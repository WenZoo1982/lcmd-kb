+++
summary = "给提交添加备注，不修改提交内容。"
+++
---

## 用途

为提交补充内部说明、审查记录等不适合写入提交说明的信息。

## 基本语法

```bash
git notes add -m "备注" <提交>
```

## 常用参数

- `show`：查看备注。
- `add -m`：添加备注。
- `edit`：编辑备注。

## 常用示例

```bash
git notes add -m "已完成回归测试" HEAD
git notes show HEAD
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-notes)。
