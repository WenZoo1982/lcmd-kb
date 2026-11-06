+++
summary = "安装、查询和删除 Debian 软件包。"
+++
---

## 用途

安装、查询和删除 Debian 软件包。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`dpkg [选项] [动作]`

## 常用参数

- -i：安装 deb
- -r：卸载但保留配置
- -P：连配置一起清除
- -l：列出包
- -L：列出文件

## 常用示例

```bash
dpkg -l 'python3*'
```

## 扩展参数

更多用法请执行 `man dpkg` 或 `dpkg --help`（命令支持时）查看。
