+++
summary = "从 Git 跟踪中删除文件。"
+++
---

## 用途

删除项目文件并把删除操作加入暂存区；也可只让 Git 停止跟踪而保留本地文件。

## 基本语法

```bash
git rm <文件>
git rm --cached <文件>
```

## 常用参数

- `--cached`：只从版本控制中移除，保留本地文件。
- `-r`：递归删除目录。
- `-f`：强制删除有本地改动的文件。

## 常用示例

```bash
git rm old.txt
git rm --cached config.local
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-rm)。
