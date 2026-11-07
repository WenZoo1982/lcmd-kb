+++
summary = "恢复位置堆栈中保存的工作目录；PowerShell 使用 Pop-Location。"
+++
---

## 用途

恢复之前由 `pushd` 保存的工作位置。Windows PowerShell 5.1 中，`popd` 是 `Pop-Location` 的别名。

## 基本语法

```powershell
popd
```

## 常用参数

`popd` 通常不需要参数，会恢复位置堆栈顶部保存的位置。

## 常用示例

```powershell
pushd D:\Project
# 在目标目录中执行操作
popd
```

执行 `popd` 后，当前工作位置恢复到执行 `pushd` 前的位置。

## 必要注意事项

必须先有由 `pushd` 或 `Push-Location` 保存的位置，才能正常恢复。CMD 和 PowerShell 都提供位置堆栈机制，但 UNC 路径处理方式可能不同。

PowerShell 完整语法：`Get-Help Pop-Location -Full`。