+++
summary = "使用 gzip 压缩或解压文件。"
+++
---

## 用途

使用 gzip 压缩或解压文件。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`gzip [选项] 文件...`

## 常用参数

- -d：解压
- -k：保留原文件
- -1 到 -9：调整压缩速度与比例

## 常用示例

```bash
gzip -k report.log
```

## 扩展参数

更多用法请执行 `man gzip` 或 `gzip --help`（命令支持时）查看。
