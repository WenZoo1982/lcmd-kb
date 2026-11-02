# LCMD Official Knowledge Base

LCMD knowledge base stores offline command-reference documents for the LCMD CLI.

> **Current status:** This repository is being reshaped for the P6 architecture. The pages in this commit are small integration fixtures for validating the directory model and query behavior; they are not the complete command catalog and do not yet define the final content-authoring standard.

## Version manifest

The repository root contains `manifest.json`, which declares the knowledge-base version:

```json
{
  "version": "0.1.0"
}
```

The version remains unchanged while the new directory and document model is under development. Compatibility/versioning rules will be finalized with the P6 schema.

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
        │   └── zh-CN/
        └── ssh/
            └── zh-CN/
```

## Directory responsibilities

- `commands/platforms/<platform>/<language>/` contains operating-system command pages. A normal platform command is one Markdown file.
- `commands/tools/<tool>/<language>/` contains third-party CLI tool documentation.
- A tool entry page uses the tool directory name, such as `tools/git/zh-CN/git.md` or `tools/docker/zh-CN/docker.md`. Complex tools can add separate Markdown files for subcommands.
- Nested subcommand paths are represented by nested directories. For example, `tools/docker/zh-CN/compose/up.md` represents `docker compose up`.
- A simple tool can use one comprehensive page named after the tool, such as `tools/ssh/zh-CN/ssh.md`.
- Platform and language directories are intended to be discovered from the knowledge base itself. No empty directories for future platforms are required.
- Tool documentation is shared across platforms by default. Platform-specific behavioral differences must be explained in the relevant page.

## Markdown page format

The current integration fixtures use UTF-8 Markdown with TOML Front Matter delimited by standalone `+++` lines. At this stage, only the existing `summary` field is used:

```markdown
+++
summary = "A concise description of what the command does."
+++

## Purpose

Describe the command and provide practical examples.
```

The final schema, navigation metadata, document identity rules, and validation requirements remain part of P6 design. Do not treat these small fixtures as a frozen authoring standard yet.

## Integration fixtures

- Windows: `dir` in Chinese and English.
- Linux: `ls` in Chinese and English.
- Git: `git.md` entry pages, plus `init` and `status` pages; English includes `git.md` and `init`.
- Docker: `docker.md` entry page, `run`, and the nested `compose up` page in Chinese.
- SSH: one comprehensive Chinese reference page without a navigation page.

These fixtures are intended to exercise platform/language discovery, tool navigation, simple-tool lookup, nested subcommand paths, and language availability differences.

## Contribution status

- [x] Establish the `platforms/` and `tools/` directory layout.
- [x] Add small platform and tool integration fixtures.
- [ ] Finalize the document schema and path/identity rules with the P6 implementation.
- [ ] Validate the new structure with the refactored LCMD CLI.
- [ ] Expand the command catalog after the architecture is frozen.
