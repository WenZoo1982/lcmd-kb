+++
summary = "对管道对象排序；PowerShell 中 sort 是 Sort-Object 的别名，注意与 sort.exe 区分。"
+++
---

## 用途

对管道中的对象进行排序。Windows PowerShell 5.1 中，`sort` 是 `Sort-Object` 的别名。

## 基本语法

```powershell
命令 | sort [[-Property] 属性] [参数]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 按名称排序 | `Get-ChildItem \| sort Name` | 按名称升序排列 |
| 按大小排序 | `Get-ChildItem -File \| sort Length` | 按文件大小排列 |
| 降序排列 | `Get-Process \| sort CPU -Descending` | 按 CPU 时间降序排列 |
| 去除重复项 | `'b','a','b' \| sort -Unique` | 排序并去重 |

## 常用示例

```powershell
Get-ChildItem -File | sort Length -Descending
Get-Service | sort Status, Name
```

## 必要注意事项

PowerShell 中的 `sort` 调用 `Sort-Object`，排序的是管道对象及其属性。Windows 自带的文本行排序程序是外部命令 `sort.exe`。

如需使用 CMD 的文本文件排序程序，请明确调用 `sort.exe`。两者参数和输入输出方式不同。

PowerShell 完整语法：`Get-Help Sort-Object -Full`。