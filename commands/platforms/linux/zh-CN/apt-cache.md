+++
summary = "查询 APT 软件包缓存。"
+++
---

## 用途

查询 APT 软件包缓存。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`apt-cache 子命令 [参数...]`

## 常用参数

- search：搜索
- show：显示详情
- policy：查看版本来源
- depends：查看依赖

## 常用示例

```bash
apt-cache policy bash
```

## 扩展参数

更多用法请执行 `man apt-cache` 或 `apt-cache --help`（命令支持时）查看。
