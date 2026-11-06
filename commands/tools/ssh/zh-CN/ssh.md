+++
summary = "连接远程计算机并执行命令。"
+++
---

## 用途

通过 SSH 加密连接远程主机，可登录交互式终端，也可直接执行远程命令。

## 基本语法

```bash
ssh [选项] [用户@]主机 [远程命令]
```

## 常用参数

- `-p 端口`：指定远程端口，默认 22。
- `-i 文件`：指定私钥文件。
- `-J 跳板机`：通过跳板机连接。
- `-L 本地端口:目标主机:目标端口`：建立本地端口转发。
- `-N`：不执行远程命令，只建立连接。
- `-v`：显示连接调试信息。
- `-o 参数=值`：临时指定配置项。

## 常用示例

```bash
ssh user@192.168.1.10
ssh -p 2222 -i ~/.ssh/id_ed25519 user@example.com
ssh user@example.com "uname -a"
ssh -J jump-user@jump.example.com user@server.example.com
ssh -N -L 8080:127.0.0.1:80 user@example.com
```

## 使用提示

首次连接时核对主机指纹；不要为了绕过警告而随意关闭主机密钥检查。

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [OpenSSH 官方手册](https://www.openssh.com/manual.html) 或对应系统的命令手册。
