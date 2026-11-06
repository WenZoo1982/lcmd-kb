+++
summary = "查看 Git 对象的类型、大小或内容。"
+++
---

## 用途

需要检查某个提交、树或对象内部内容时使用，属于偏底层的排查工具。

## 基本语法

```bash
git cat-file -t <对象>
git cat-file -p <对象>
```

## 常用参数

- `-t`：查看对象类型。
- `-s`：查看对象大小。
- `-p`：按可读形式显示对象内容。

## 常用示例

```bash
git cat-file -t HEAD
git cat-file -p HEAD
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-cat-file)。
