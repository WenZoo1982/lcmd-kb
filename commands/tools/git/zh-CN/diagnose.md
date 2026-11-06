+++
summary = "打包仓库诊断信息。"
+++
---

## 用途

需要向他人提供仓库状态、对象统计等诊断材料时使用。注意检查压缩包是否包含不应公开的信息。

## 基本语法

```bash
git diagnose
```

## 常用参数

- `--output-directory=<目录>`：指定输出目录。
- `--mode=<模式>`：选择诊断信息范围。

## 常用示例

```bash
git diagnose --output-directory=reports
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-diagnose)。
