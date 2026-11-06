+++
summary = "应用邮件格式的补丁。"
+++
---

## 用途

接收通过邮件发送的 Git 补丁，常用于邮件协作流程。

## 基本语法

```bash
git am <补丁文件>
git am < 补丁文件
```

## 常用参数

- `-3`：应用失败时尝试三方合并。
- `--abort`：放弃当前补丁应用。
- `--continue`：解决冲突后继续。

## 常用示例

```bash
git am 0001-fix.patch
git am --abort
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-am)。
