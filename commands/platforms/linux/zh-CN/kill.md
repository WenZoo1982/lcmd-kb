+++
summary = "向进程发送信号。"
+++
---

## 用途

向进程发送信号。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`kill [选项] PID...`

## 常用参数

- -TERM：请求正常终止
- -KILL：强制终止
- -l：列出信号

## 常用示例

```bash
kill -TERM 1234
```

## 扩展参数

更多用法请执行 `man kill` 或 `kill --help`（命令支持时）查看。
