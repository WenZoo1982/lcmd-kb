# LCMD Official Knowledge Base

The LCMD knowledge base stores command reference pages and task guides. It is organized by platform and language, with a shared `common` collection used as a fallback when a platform-specific page is absent.

> **Current status:** this repository contains the initial structure and a small set of English sample pages for integration testing. The broader command and task catalog will be added incrementally.

## Version manifest

The repository root contains `manifest.json`, which declares the knowledge-base version:

```json
{
  "version": "0.1.0"
}
```

Versions follow Semantic Versioning 2.0.0. The current application checks Major-version compatibility between the application and the knowledge base.

## Directory layout

```text
lcmd-kb/
├── manifest.json
├── README.md
├── commands/
│   ├── common/{en-US,zh-CN}/
│   ├── linux/{en-US,zh-CN}/
│   ├── windows/{en-US,zh-CN}/
│   └── macos/{en-US,zh-CN}/
└── tasks/
    ├── common/{en-US,zh-CN}/
    ├── linux/{en-US,zh-CN}/
    ├── windows/{en-US,zh-CN}/
    └── macos/{en-US,zh-CN}/
```

## Platform and language rules

- `commands/` contains command reference pages; `tasks/` contains task guides.
- Supported platform directory names are `common`, `linux`, `windows`, and `macos`.
- `en-US/` contains English pages; `zh-CN/` contains Simplified Chinese pages.
- Platform-specific pages take precedence over pages with the same filename in `common`.
- If a platform-specific page is absent, the application may use the matching `common` page as a fallback.
- The current loader scans only top-level `*.md` files in each platform/language directory; it does not recurse into nested directories.

## Markdown page format

Each page uses TOML Front Matter delimited by standalone `+++` lines.

A command page requires a non-empty `summary` and a non-empty Markdown body:

```markdown
+++
summary = "Display files and directories in the current location."
+++

## Basic syntax

Describe the command syntax and practical examples here.
```

A task page also requires `summary` and a non-empty body. It may include a `commands` array of command names:

```markdown
+++
summary = "List files in the current directory."
commands = ["dir"]
+++

## Steps

Describe the task procedure here.
```

## English sample pages

These short pages are integration-test samples, not a complete command reference:

- `commands/windows/en-US/dir.md`: Windows-specific `dir` page.
- `commands/common/en-US/dir.md`: same-name shared fallback for checking platform precedence.
- `commands/common/en-US/git.md`: shared command page for checking common fallback.
- `tasks/windows/en-US/list-files.md`: sample task page.

## Contribution status

- [x] Create the knowledge-base root and version manifest.
- [x] Create command and task directories for common, Linux, Windows, and macOS.
- [x] Add `zh-CN` and `en-US` language directories.
- [x] Add a minimal set of English sample pages for integration testing.
- [ ] Gradually expand and validate the command catalog.
- [ ] Gradually expand and validate the task catalog.
