+++
summary = "直接修改 Git 索引信息。"
+++
---

## 用途

处理特殊索引场景或脚本自动化时使用；普通文件暂存优先使用 `git add`。

## 基本语法

```bash
git update-index <选项>
```

## 常用参数

- `--assume-unchanged`：提示 Git 暂不检查文件变化，不适合当作忽略规则。
- `--no-assume-unchanged`：取消上述标记。

## 常用示例

```bash
git update-index --assume-unchanged local-config.ini
git update-index --no-assume-unchanged local-config.ini
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-update-index)。
