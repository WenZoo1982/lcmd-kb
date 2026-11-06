+++
summary = "管理嵌套在当前仓库中的其他 Git 仓库。"
+++
---

## 用途

项目依赖另一个独立 Git 仓库，且需要固定其版本时使用。

## 基本语法

```bash
git submodule add <仓库地址> <目录>
git submodule update --init --recursive
```

## 常用参数

- `add`：添加子模块。
- `update --init`：初始化并检出子模块。
- `--recursive`：同时处理嵌套子模块。
- `status`：查看子模块状态。

## 常用示例

```bash
git submodule add https://github.com/user/lib.git libs/lib
git submodule update --init --recursive
git submodule status
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-submodule)。
