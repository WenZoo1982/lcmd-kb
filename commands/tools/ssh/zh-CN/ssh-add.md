+++
summary = "向 SSH 代理添加或管理私钥。"
+++
---

## 用途

将私钥加载到 ssh-agent，供 SSH 连接使用；也可查看或移除代理中的密钥。

## 基本语法

```bash
ssh-add [选项] [私钥文件...]
```

## 常用参数

- `-l`：列出代理中密钥的指纹。
- `-L`：列出代理中的公钥。
- `-d 文件`：移除指定密钥。
- `-D`：移除代理中的全部密钥。
- `-t 时间`：设置密钥在代理中的有效时长。

## 常用示例

```bash
ssh-add ~/.ssh/id_ed25519
ssh-add -l
ssh-add -L
ssh-add -t 1h ~/.ssh/id_ed25519
ssh-add -d ~/.ssh/id_ed25519
ssh-add -D
```

## 使用提示

执行前需要有可用的 ssh-agent；不要把私钥内容复制到命令参数或聊天记录中。

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [OpenSSH 官方手册](https://www.openssh.com/manual.html) 或对应系统的命令手册。
