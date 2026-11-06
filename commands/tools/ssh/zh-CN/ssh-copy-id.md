+++
summary = "把本机公钥安装到远程账户。"
+++
---

## 用途

将公钥追加到远程账户的 authorized_keys，便于之后使用密钥登录。

## 基本语法

```bash
ssh-copy-id [选项] [用户@]主机
```

## 常用参数

- `-i 文件`：指定要安装的公钥文件。
- `-p 端口`：指定远程 SSH 端口。
- `-n`：只预览，不实际安装。
- `-f`：强制安装，不检查远程端是否已有该密钥。

## 常用示例

```bash
ssh-copy-id user@example.com
ssh-copy-id -i ~/.ssh/id_ed25519.pub user@example.com
ssh-copy-id -p 2222 user@example.com
ssh-copy-id -n user@example.com
```

## 使用提示

该命令并非所有 OpenSSH 安装都包含；Windows 原生 OpenSSH 通常没有，可手动部署公钥。

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [OpenSSH 官方手册](https://www.openssh.com/manual.html) 或对应系统的命令手册。
