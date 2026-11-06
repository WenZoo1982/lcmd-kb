+++
summary = "查询 systemd 日志。"
+++
---

## 用途

查询 systemd 日志。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`journalctl [选项]`

## 常用参数

- -u：按单元筛选
- -b：本次启动
- -n：最近行数
- -f：持续跟踪

## 常用示例

```bash
journalctl -u ssh -n 50
```

## 扩展参数

更多用法请执行 `man journalctl` 或 `journalctl --help`（命令支持时）查看。
