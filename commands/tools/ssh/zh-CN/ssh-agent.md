+++
summary = "在后台暂存已解锁的 SSH 私钥。"
+++
---

## 用途

启动密钥代理，让后续 SSH 连接复用已解锁的密钥，减少重复输入私钥口令。

## 基本语法

```bash
ssh-agent [选项] [命令 [参数...]]
```

## 常用参数

- `-s`：输出适用于 Bourne shell 的环境变量设置。
- `-c`：输出适用于 C shell 的环境变量设置。
- `-k`：结束当前代理进程（需有代理环境变量）。

## 常用示例

```bash
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
ssh-add -l
ssh-agent -k
```

## 使用提示

Windows 的 OpenSSH Authentication Agent 通常由 Windows 服务管理；Linux/macOS 常见用法与 shell 环境有关。

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [OpenSSH 官方手册](https://www.openssh.com/manual.html) 或对应系统的命令手册。
