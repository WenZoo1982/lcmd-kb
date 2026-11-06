+++
summary = "查找文件和目录。"
+++
---

## 用途

查找文件和目录。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`find [路径] [条件] [动作]`

## 常用参数

- -name：按名称匹配
- -type：按类型筛选
- -mtime：按修改时间筛选

## 常用示例

```bash
find . -type f -name '*.log'
```

## 扩展参数

更多用法请执行 `man find` 或 `find --help`（命令支持时）查看。
