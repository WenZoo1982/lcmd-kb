+++
summary = "查看 HEAD 和分支引用的移动记录。"
+++
---

## 用途

误切分支、误重置或提交似乎丢失时，查找之前的位置以便恢复。

## 基本语法

```bash
git reflog
git reflog <分支>
```

## 常用参数

- `--all`：查看所有引用的记录。
- `--date=local`：使用本地时间显示。

## 常用示例

```bash
git reflog
git reflog --date=local
# 找到目标记录后，可用其提交号恢复
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-reflog)。
