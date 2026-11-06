+++
summary = "删除用户账户。"
+++
---

## 用途

删除用户账户。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`sudo userdel [选项] 用户`

## 常用参数

- -r：同时删除主目录和邮件目录

## 常用示例

```bash
sudo userdel -r olduser
```

## 扩展参数

更多用法请执行 `man userdel` 或 `userdel --help`（命令支持时）查看。
