+++
summary = "列出文件和目录；PowerShell 使用 Get-ChildItem，并补充 CMD dir 的差异。"
+++
---

## 用途

列出当前目录或指定目录中的文件和子目录。Windows PowerShell 5.1 中，`dir` 是 `Get-ChildItem` 的常用别名。

## 基本语法

```powershell
dir [[-Path] 路径] [参数]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 查看当前目录 | `dir` | 显示当前目录内容 |
| 查看指定目录 | `dir D:\Downloads` | 列出指定目录内容 |
| 只显示文件 | `dir -File` | 排除目录 |
| 只显示文件夹 | `dir -Directory` | 只列出子目录 |
| 包含隐藏项 | `dir -Force` | 包括隐藏项和系统项 |
| 递归查看 | `dir -Recurse` | 同时列出子目录内容 |
| 按名称筛选 | `dir -Filter *.zip` | 只列出匹配的项目 |

## 常用示例

```powershell
dir -File -Filter *.zip
dir D:\Downloads -Directory
dir . -Recurse -Filter *.log
```

只列出当前目录中扩展名为 .zip 的文件。

## 必要注意事项

PowerShell 中的 `dir` 遵循 `Get-ChildItem` 参数规则，例如使用 `-File`、`-Directory`、`-Recurse`。

CMD 中的 `dir` 是另一套内部命令，常用参数为 `/a`、`/s`、`/b`、`/o` 等。不要将 CMD 的斜杠参数直接用于 PowerShell。需要查看 CMD 帮助时，使用 `cmd /c dir /?`。

PowerShell 完整语法：`Get-Help Get-ChildItem -Full`。