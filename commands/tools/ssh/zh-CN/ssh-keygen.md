+++
summary = "生成、管理和检查 SSH 密钥。"
+++
---

## 用途

创建公钥/私钥对，用于免密码登录、身份验证或服务端主机密钥管理。

## 基本语法

```bash
ssh-keygen [选项]
```

## 常用参数

- `-t ed25519`：生成 Ed25519 密钥，通常优先用于新用户密钥。
- `-C 注释`：添加密钥说明。
- `-f 文件`：指定密钥保存路径。
- `-a 次数`：设置口令派生计算次数。
- `-p`：修改现有私钥口令。
- `-l -f 文件`：显示密钥指纹。
- `-R 主机`：从 known_hosts 移除主机记录。

## 常用示例

```bash
ssh-keygen -t ed25519 -C "my-laptop"
ssh-keygen -t ed25519 -f ~/.ssh/server_key
ssh-keygen -p -f ~/.ssh/id_ed25519
ssh-keygen -lf ~/.ssh/id_ed25519.pub
ssh-keygen -R example.com
```

## 使用提示

私钥必须妥善保管，不要发送给他人；通常只把对应的 `.pub` 公钥部署到远程主机。

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [OpenSSH 官方手册](https://www.openssh.com/manual.html) 或对应系统的命令手册。
