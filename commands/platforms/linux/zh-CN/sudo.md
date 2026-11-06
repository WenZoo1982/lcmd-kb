+++
summary = "以提升的权限运行命令。"
+++
---

## 用途

以提升的权限运行命令。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`sudo [选项] 命令 [参数...]`

## 常用参数

- -u：指定运行用户
- -i：启动登录 shell
- -k：使缓存凭据失效

## 常用示例

```bash
sudo apt update
```

## 扩展参数

更多用法请执行 `man sudo` 或 `sudo --help`（命令支持时）查看。
