+++
summary = "把提交导出为可通过邮件发送的补丁文件。"
+++
---

## 用途

适合不通过共享远程分支、而是通过补丁文件交换代码的协作方式。

## 基本语法

```bash
git format-patch <范围或提交>
```

## 常用参数

- `-1`：只导出最近一次提交。
- `-o <目录>`：指定输出目录。
- `--stdout`：输出到终端或管道。

## 常用示例

```bash
git format-patch -1 HEAD
git format-patch -o patches origin/main..HEAD
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-format-patch)。
