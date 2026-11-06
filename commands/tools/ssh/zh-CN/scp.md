+++
summary = "通过 SSH 在本机与远程主机之间复制文件。"
+++
---

## 用途

适合快速上传或下载文件、目录；传输使用 SSH 加密连接。

## 基本语法

```bash
scp [选项] 源路径 目标路径
```

## 常用参数

- `-P 端口`：指定远程端口（大写 P）。
- `-i 文件`：指定私钥文件。
- `-r`：递归复制目录。
- `-p`：保留文件时间和权限。
- `-C`：启用压缩传输。
- `-J 跳板机`：通过跳板机连接。

## 常用示例

```bash
scp report.txt user@example.com:/home/user/
scp user@example.com:/var/log/app.log .
scp -r ./website user@example.com:/var/www/
scp -P 2222 backup.zip user@example.com:/data/
```

## 使用提示

较新版本 OpenSSH 默认使用 SFTP 协议实现 scp，旧版行为可能不同。复制前确认目标路径和覆盖风险。

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [OpenSSH 官方手册](https://www.openssh.com/manual.html) 或对应系统的命令手册。
