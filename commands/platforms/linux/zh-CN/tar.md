+++
summary = "创建或解压 tar 归档。"
+++
---

## 用途

创建或解压 tar 归档。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`tar [选项] 归档文件 [文件...]`

## 常用参数

- -c：创建
- -x：解压
- -t：列出
- -f：指定归档
- -z：gzip

## 常用示例

```bash
tar -czf backup.tar.gz project/
```

## 扩展参数

更多用法请执行 `man tar` 或 `tar --help`（命令支持时）查看。
