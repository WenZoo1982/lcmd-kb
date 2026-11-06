+++
summary = "收集远程 SSH 服务的主机公钥。"
+++
---

## 用途

批量获取主机公钥，常用于核验指纹或准备 known_hosts 文件。

## 基本语法

```bash
ssh-keyscan [选项] 主机...
```

## 常用参数

- `-p 端口`：指定 SSH 服务端口。
- `-t 类型`：指定密钥类型，如 ed25519、rsa。
- `-H`：对输出中的主机名进行哈希处理。
- `-f 文件`：从文件读取主机列表。
- `-4` / `-6`：仅使用 IPv4 / IPv6。

## 常用示例

```bash
ssh-keyscan example.com
ssh-keyscan -p 2222 -t ed25519 example.com
ssh-keyscan example.com >> ~/.ssh/known_hosts
ssh-keyscan -H example.com >> ~/.ssh/known_hosts
```

## 使用提示

`ssh-keyscan` 获取到的密钥本身不能证明服务器身份。写入前应通过可信渠道核对指纹，避免中间人攻击。

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [OpenSSH 官方手册](https://www.openssh.com/manual.html) 或对应系统的命令手册。
