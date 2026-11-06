+++
summary = "检查仓库对象和数据完整性。"
+++
---

## 用途

怀疑仓库对象损坏或数据异常时，用于检查对象数据库。

## 基本语法

```bash
git fsck
```

## 常用参数

- `--full`：执行完整检查。
- `--no-reflogs`：不把 reflog 引用作为可达性依据。

## 常用示例

```bash
git fsck --full
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-fsck)。
