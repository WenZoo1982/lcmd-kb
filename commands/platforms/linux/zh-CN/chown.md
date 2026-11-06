+++
summary = "修改文件所有者和所属组。"
+++
---

## 用途

修改文件所有者和所属组。适用于 Debian、Ubuntu 和 Linux Mint。

## 基本语法

`chown [选项] 用户[:组] 文件...`

## 常用参数

- -R：递归修改
- --reference：参照另一文件的属主

## 常用示例

```bash
sudo chown -R user:user data/
```

## 扩展参数

更多用法请执行 `man chown` 或 `chown --help`（命令支持时）查看。
