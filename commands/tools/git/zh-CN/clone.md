+++
summary = "下载远程仓库到本地。"
+++
---

## 用途

首次获取 GitHub 等平台上的项目时使用。

## 基本语法

```bash
git clone <仓库地址>
git clone <仓库地址> <目录>
```

## 常用参数

- `-b <分支>`：克隆后切换到指定分支。
- `--depth 1`：只获取最近一层提交，减少下载量。
- `--recurse-submodules`：同时初始化子模块。

## 常用示例

```bash
git clone https://github.com/user/project.git
git clone -b dev https://github.com/user/project.git
git clone --depth 1 <仓库地址>
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-clone)。
