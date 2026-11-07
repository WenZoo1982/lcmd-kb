# LCMD Official Knowledge Base

LCMD knowledge base stores offline command-reference documents for the LCMD CLI.

## Current content

The repository contains 578 Markdown command-reference documents across operating-system commands and common CLI tools.

| Category | Language | Documents |
|---|---:|---:|
| Linux platform commands | zh-CN | 47 |
| Linux platform commands | en-US | 47 |
| Windows platform commands | zh-CN | 123 |
| Windows platform commands | en-US | 102 |
| Docker | zh-CN | 59 |
| Docker | en-US | 58 |
| Git | zh-CN | 62 |
| Git | en-US | 62 |
| SSH | zh-CN | 9 |
| SSH | en-US | 9 |

Platform-specific commands are stored under `commands/platforms/<platform>/<language>/`. Shared CLI tool references are stored under `commands/tools/<tool>/<language>/`.

## Version manifest

The repository root contains `manifest.json`, which declares the knowledge-base version. The current manifest version remains `0.1.0`; a new release version should be assigned when preparing the next versioned knowledge-base release.

## Directory layout

```text
lcmd-kb/
├── manifest.json
└── commands/
    ├── platforms/
    │   ├── windows/
    │   │   ├── zh-CN/
    │   │   └── en-US/
    │   └── linux/
    │       ├── zh-CN/
    │       └── en-US/
    └── tools/
        ├── git/
        │   ├── zh-CN/
        │   └── en-US/
        ├── docker/
        │   ├── zh-CN/
        │   └── en-US/
        └── ssh/
            ├── zh-CN/
            └── en-US/
```

## Directory responsibilities

- `commands/platforms/<platform>/<language>/` contains operating-system command pages. A normal platform command is one Markdown file.
- `commands/tools/<tool>/<language>/` contains third-party CLI tool documentation.
- A tool entry page uses the tool directory name, such as `tools/git/zh-CN/git.md` or `tools/docker/zh-CN/docker.md`. Complex tools can add separate files for subcommands.
- Nested subcommand paths are represented by nested directories. For example, `tools/docker/zh-CN/compose/up.md` represents `docker compose up`.
- A simple tool can use one comprehensive page named after the tool, such as `tools/ssh/zh-CN/ssh.md`.
- Platform and language directories are discovered from the knowledge base itself. Empty directories for future platforms are not required.
- Tool documentation is shared across platforms by default. Platform-specific behavioral differences should be explained in the relevant page.

## Markdown page format

Documents use UTF-8 Markdown with TOML Front Matter delimited by standalone `+++` lines. The `summary` field provides a concise description used by LCMD for command discovery.

```markdown
+++
summary = "A concise description of what the command does."
+++
---

## Purpose

Describe the command and provide practical examples.
```

## Content maintenance

- Keep command pages focused on practical command usage and commonly needed options.
- Provide Chinese and English documents where available.
- Explain platform-specific behavior and important safety considerations.
- Validate TOML Front Matter and Markdown structure before publishing changes.
