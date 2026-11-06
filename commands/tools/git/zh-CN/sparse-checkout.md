+++
summary = "只检出仓库中的部分目录或文件。"
+++
---

## 用途

仓库很大但当前只需要其中一部分内容时减少本地工作区体积。

## 基本语法

```bash
git sparse-checkout init --cone
git sparse-checkout set <目录>
```

## 常用参数

- `init --cone`：启用目录模式，适合大多数场景。
- `set`：设置要检出的目录。
- `disable`：关闭稀疏检出。

## 常用示例

```bash
git sparse-checkout init --cone
git sparse-checkout set src docs
git sparse-checkout disable
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-sparse-checkout)。
