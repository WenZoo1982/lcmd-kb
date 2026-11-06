+++
summary = "创建文件链接。"
+++
---

## 用途

创建文件链接。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`ln [选项] 目标 链接名`

## 常用参数

- -s：创建符号链接
- -f：覆盖已有链接

## 常用示例

```bash
ln -s /var/log/syslog syslog
```

## 扩展参数

更多用法请执行 `man ln` 或 `ln --help`（命令支持时）查看。
