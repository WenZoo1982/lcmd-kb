+++
summary = "按文本模式搜索内容。"
+++
---

## 用途

按文本模式搜索内容。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`grep [选项] 模式 [文件...]`

## 常用参数

- -i：忽略大小写
- -n：显示行号
- -r：递归搜索
- -v：反向匹配

## 常用示例

```bash
grep -in 'error' app.log
```

## 扩展参数

更多用法请执行 `man grep` 或 `grep --help`（命令支持时）查看。
