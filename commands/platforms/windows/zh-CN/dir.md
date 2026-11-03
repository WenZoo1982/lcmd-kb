+++
summary = "查看当前目录中的文件和子目录，并按名称、类型或时间筛选。"
+++
---

## 用途

列出当前目录或指定目录中的文件和子目录。PowerShell 中的 `dir` 是 `Get-ChildItem` 的常用别名。

## 基本语法

```powershell
dir [路径] [参数]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 查看当前目录 | `dir` | 显示当前目录内容 |
| 查看指定目录 | `dir D:\\Downloads` | 列出指定目录内容 |
| 只显示文件 | `dir -File` | 排除目录 |
| 只显示文件夹 | `dir -Directory` | 只列出子目录 |

## 常用示例

```powershell
dir -File -Filter *.zip
```

只列出当前目录中扩展名为 `.zip` 的文件。

## 必要注意事项

这里的参数遵循 Windows PowerShell 5.1 的 `Get-ChildItem` 规则，不要直接套用 CMD 内部命令的参数规则。
