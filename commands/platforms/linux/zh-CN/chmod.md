+++
summary = "修改文件权限。"
+++
---

## 用途

修改文件权限。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`chmod [选项] 模式 文件...`

## 常用参数

- -R：递归修改
- 模式可用数字（如 755）或符号（如 u+x）

## 常用示例

```bash
chmod 755 script.sh
```

## 扩展参数

更多用法请执行 `man chmod` 或 `chmod --help`（命令支持时）查看。
