+++
summary = "列出块设备。"
+++
---

## 用途

列出块设备。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`lsblk [选项] [设备...]`

## 常用参数

- -f：显示文件系统信息
- -o：选择列
- -p：显示完整设备路径

## 常用示例

```bash
lsblk -f
```

## 扩展参数

更多用法请执行 `man lsblk` 或 `lsblk --help`（命令支持时）查看。
