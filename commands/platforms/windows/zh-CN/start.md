+++
summary = "启动程序或打开文件、目录、网址；PowerShell 中 start 是 Start-Process 的别名。"
+++
---

## 用途

启动进程，或使用 Windows 关联程序打开文件、目录和网址。Windows PowerShell 5.1 中，`start` 是 `Start-Process` 的别名。

## 基本语法

```powershell
start [-FilePath] 程序或文件 [参数]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 启动程序 | `start notepad.exe` | 启动记事本 |
| 打开目录 | `start .` | 使用默认文件管理器打开当前目录 |
| 打开网址 | `start https://example.com` | 使用默认浏览器打开网址 |
| 指定参数 | `start powershell.exe -ArgumentList '-NoProfile'` | 向程序传递启动参数 |
| 等待进程结束 | `start notepad.exe -Wait` | 等待启动的进程结束 |

## 常用示例

```powershell
start notepad.exe
start D:\Downloads
start https://learn.microsoft.com/powershell/
```

## 必要注意事项

CMD 的 `start` 有窗口标题等特殊语法，尤其是第一个带引号的参数可能被解释为窗口标题。PowerShell 的 `start` 调用 `Start-Process`，语法不同，不要直接复制 CMD 的参数组合。

PowerShell 完整语法：`Get-Help Start-Process -Full`。