+++
summary = "使用外部图形工具比较文件差异。"
+++
---

## 用途

不想在终端阅读差异时，调用配置好的图形比较工具。

## 基本语法

```bash
git difftool [比较范围]
```

## 常用参数

- `--tool=<工具>`：指定比较工具。
- `--dir-diff`：以目录方式比较。
- `--no-prompt`：不逐个询问是否启动工具。

## 常用示例

```bash
git difftool
git difftool --staged
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-difftool)。
