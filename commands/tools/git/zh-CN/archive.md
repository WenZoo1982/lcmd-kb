+++
summary = "把指定版本的文件打包导出。"
+++
---

## 用途

不包含 `.git` 历史记录地导出项目文件，适合制作源码包。

## 基本语法

```bash
git archive --format=<格式> --output=<压缩包> <版本>
```

## 常用参数

- `--format=zip`：生成 ZIP。
- `--format=tar`：生成 TAR。
- `--prefix=<目录>/`：在压缩包内统一添加目录前缀。

## 常用示例

```bash
git archive --format=zip --output=source.zip HEAD
git archive --format=tar --prefix=project/ -o source.tar HEAD
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-archive)。
