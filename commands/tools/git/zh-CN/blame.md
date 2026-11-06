+++
summary = "查看文件每一行最后由谁修改。"
+++
---

## 用途

排查某行代码的来源、修改者和对应提交。

## 基本语法

```bash
git blame <文件>
git blame -L <起始行>,<结束行> <文件>
```

## 常用参数

- `-L`：只查看指定行范围。
- `-w`：忽略空白字符变化。
- `-e`：显示邮箱地址。

## 常用示例

```bash
git blame src/main.py
git blame -L 20,40 README.md
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-blame)。
