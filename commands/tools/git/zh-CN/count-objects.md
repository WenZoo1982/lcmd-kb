+++
summary = "查看仓库对象数量和磁盘占用。"
+++
---

## 用途

排查 `.git` 目录占用较大时，查看松散对象和打包文件的占用情况。

## 基本语法

```bash
git count-objects -v
```

## 常用参数

- `-v`：显示详细统计。
- `-H`：使用易读的容量单位。

## 常用示例

```bash
git count-objects -vH
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-count-objects)。
