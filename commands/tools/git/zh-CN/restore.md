+++
summary = "恢复工作区文件或取消文件暂存。"
+++
---

## 用途

撤销文件未提交的修改，或把已暂存的文件移回未暂存状态。

## 基本语法

```bash
git restore <文件>
git restore --staged <文件>
```

## 常用参数

- `--staged`：取消暂存，不修改工作区文件。
- `--source=<版本>`：从指定提交恢复。
- `--worktree`：恢复工作区文件。

## 常用示例

```bash
git restore README.md
git restore --staged README.md
git restore --source=HEAD~1 README.md
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-restore)。
