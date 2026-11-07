+++
summary = "保存当前位置并切换到新目录；PowerShell 使用 Push-Location。"
+++
---

## 用途

保存当前工作位置，然后切换到指定目录。Windows PowerShell 5.1 中，`pushd` 是 `Push-Location` 的别名。

## 基本语法

```powershell
pushd 路径
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 保存并切换目录 | `pushd D:\Project` | 保存原位置并进入目标目录 |
| 切换到上级目录 | `pushd ..` | 保存当前位置后进入父目录 |
| 查看当前位置 | `pwd` | 显示当前工作位置 |

## 常用示例

```powershell
pushd D:\Project
# 完成操作后恢复原位置
popd
```

## 必要注意事项

`pushd` 会将当前位置压入位置堆栈，之后可使用 `popd` 恢复。CMD 的 `pushd` 在处理 UNC 网络路径时还可能自动分配临时驱动器号；PowerShell 的行为与 CMD 不完全相同。

PowerShell 完整语法：`Get-Help Push-Location -Full`。