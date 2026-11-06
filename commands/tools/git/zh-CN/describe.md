+++
summary = "用容易识别的名称描述当前提交。"
+++
---

## 用途

根据最近的标签生成版本描述，常用于查看构建版本或标记发布版本。

## 基本语法

```bash
git describe
git describe --tags
```

## 常用参数

- `--tags`：也使用轻量标签。
- `--always`：没有可用标签时显示提交缩写。
- `--dirty`：工作区有未提交改动时追加标记。

## 常用示例

```bash
git describe --tags
git describe --tags --dirty
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-describe)。
