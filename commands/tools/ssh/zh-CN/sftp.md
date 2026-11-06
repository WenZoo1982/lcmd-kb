+++
summary = "通过 SSH 安全地传输和管理远程文件。"
+++
---

## 用途

进入交互式文件传输会话，可浏览目录、上传、下载、重命名和删除远程文件。

## 基本语法

```bash
sftp [选项] [用户@]主机
```

## 常用参数

- `-P 端口`：指定远程端口。
- `-i 文件`：指定私钥文件。
- `-b 文件`：从批处理文件读取 SFTP 命令。
- `-J 跳板机`：通过跳板机连接。

## 常用示例

```bash
sftp user@example.com
# 会话内常用命令
pwd
lpwd
ls
cd /var/www
lcd ./website
put index.html
get access.log
put -r ./assets
get -r ./backup
bye
sftp -P 2222 user@example.com
```

## 使用提示

`put` 上传本地文件，`get` 下载远程文件；`lpwd`、`lcd` 操作本地目录，`pwd`、`cd` 操作远程目录。

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [OpenSSH 官方手册](https://www.openssh.com/manual.html) 或对应系统的命令手册。
