+++
summary = "创建、查看或删除版本标签。"
+++
---

## 用途

给重要版本或发布节点打标签，方便后续查找和发布。

## 基本语法

```bash
git tag
git tag <标签名>
git tag -d <标签名>
```

## 常用参数

- `-a`：创建附注标签。
- `-m`：填写标签说明。
- `-d`：删除本地标签。
- `--list`：筛选查看标签。

## 常用示例

```bash
git tag
git tag -a v1.0.0 -m "正式发布 1.0.0"
git push origin v1.0.0
git tag -d v1.0.0
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-tag)。
