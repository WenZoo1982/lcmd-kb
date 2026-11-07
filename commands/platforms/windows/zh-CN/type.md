+++
summary = "读取文本文件内容；PowerShell 使用 Get-Content，并补充 CMD type 的差异。"
+++
---

## 用途

读取并显示文本文件内容。Windows PowerShell 5.1 中，`type` 是 `Get-Content` 的别名。

## 基本语法

```powershell
type [-Path] 文件路径 [参数]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 查看文件 | `type .\app.log` | 输出文件内容 |
| 查看开头 | `type .\app.log -TotalCount 20` | 只读取前 20 行 |
| 查看末尾 | `type .\app.log -Tail 50` | 读取最后 50 行 |
| 持续查看 | `type .\app.log -Wait -Tail 20` | 等待并显示新增内容 |
| 作为整体读取 | `type .\app.log -Raw` | 返回单个字符串 |

## 常用示例

```powershell
type .\README.txt
type .\app.log -Tail 30
```

## 必要注意事项

PowerShell 的 `type` 调用 `Get-Content`，可将读取结果继续传递给管道中的其他命令。

CMD 的 `type` 主要用于显示文本文件，不支持 PowerShell 的 `-Tail`、`-Wait`、`-Raw` 等参数。

PowerShell 完整语法：`Get-Help Get-Content -Full`。