+++
summary = "显示文件末尾内容。"
+++
---

## 用途

显示文件末尾内容。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`tail [选项] [文件...]`

## 常用参数

- -n：指定行数
- -f：持续跟踪新增内容

## 常用示例

```bash
tail -f /var/log/syslog
```

## 扩展参数

更多用法请执行 `man tail` 或 `tail --help`（命令支持时）查看。
