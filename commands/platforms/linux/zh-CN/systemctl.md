+++
summary = "管理 systemd 服务与单元。"
+++
---

## 用途

管理 systemd 服务与单元。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`systemctl [选项] 子命令 [单元]`

## 常用参数

- status：查看状态
- start/stop/restart：控制服务
- enable/disable：设置开机启动

## 常用示例

```bash
sudo systemctl status ssh
```

## 扩展参数

更多用法请执行 `man systemctl` 或 `systemctl --help`（命令支持时）查看。
