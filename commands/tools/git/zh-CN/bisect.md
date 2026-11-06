+++
summary = "用二分法定位引入问题的提交。"
+++
---

## 用途

当你知道某个旧版本正常、当前版本异常时，快速找出问题提交。

## 基本语法

```bash
git bisect start
git bisect bad [版本]
git bisect good <正常版本>
```

## 常用参数

- `start`：开始定位。
- `bad`：标记当前版本有问题。
- `good`：标记已知正常版本。
- `reset`：结束定位并返回原分支。

## 常用示例

```bash
git bisect start
git bisect bad
git bisect good v1.2.0
# 按提示测试每个版本并标记 good/bad
git bisect reset
```

## 更多参数

本文仅收录常用参数。如需了解完整参数及详细说明，请查阅 [Git 官方文档](https://git-scm.com/docs/git-bisect)。
