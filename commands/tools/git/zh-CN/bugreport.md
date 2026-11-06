+++
summary = "收集 Git 环境信息用于提交问题报告。"
+++
---

## 用途

Git 本身出现异常，需要向维护者提供版本、环境和配置摘要时使用。

## 基本语法

```bash
git bugreport
```

## 常用参数

- `-o <目录>`：指定报告输出目录。
- `-s <主题>`：设置报告主题。

## 常用示例

```bash
git bugreport -o reports
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-bugreport)。
