+++
summary = "Start a process or open a file, directory, or URL; in PowerShell, start is an alias for Start-Process."
+++
---

## Purpose

Start a process, or open a file, directory, or URL with its associated application. In Windows PowerShell 5.1, start is an alias for Start-Process.

## Basic syntax

~~~powershell
start [-FilePath] PROGRAM_OR_FILE [OPTIONS]
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Start an application | start notepad.exe | Start Notepad |
| Open a directory | start . | Open the current directory in the default file manager |
| Open a URL | start https://example.com | Open the URL in the default browser |
| Pass arguments | start powershell.exe -ArgumentList '-NoProfile' | Pass startup arguments to the process |
| Wait for the process | start notepad.exe -Wait | Wait for the started process to exit |

## Common examples

~~~powershell
start notepad.exe
start D:\Downloads
start https://learn.microsoft.com/powershell/
~~~

## Notes

CMD start has special window-title syntax. In particular, its first quoted argument may be interpreted as a window title. PowerShell start invokes Start-Process and uses different syntax; do not copy CMD argument combinations directly.

Full PowerShell syntax: Get-Help Start-Process -Full.