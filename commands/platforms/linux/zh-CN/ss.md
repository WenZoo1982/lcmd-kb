+++
summary = "查看套接字与网络连接。"
+++
---

## 用途

查看套接字与网络连接。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`ss [选项]`

## 常用参数

- -t：TCP
- -u：UDP
- -l：监听
- -n：不解析名称
- -p：显示进程

## 常用示例

```bash
ss -tulnp
```

## 扩展参数

更多用法请执行 `man ss` 或 `ss --help`（命令支持时）查看。
