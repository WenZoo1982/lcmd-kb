# LCMD Official Knowledge Base

LCMD knowledge base stores Markdown command reference pages. It is organized by platform and language, with a shared `common` collection used only when a platform-specific command page is absent.

> **First-release scope:** Windows x64 and Linux AMD64. Supported documentation languages are Simplified Chinese (`zh-CN`) and English (`en-US`).

## Version manifest

The repository root contains `manifest.json`, which declares the knowledge-base version:

```json
{
  "version": "0.1.0"
}
```

Versions follow Semantic Versioning 2.0.0. The application checks Major-version compatibility between the application and the knowledge base.

## Directory layout

```text
lcmd-kb/
├── manifest.json
├── README.md
└── commands/
    ├── common/{en-US,zh-CN}/
    ├── linux/{en-US,zh-CN}/
    └── windows/{en-US,zh-CN}/
```

## Platform and language rules

- `commands/` is the only knowledge-document directory. The repository does not use a separate `tasks/` document type or directory.
- First-release platform directories are `common`, `linux`, and `windows`. The `common` directory is for cross-platform tools such as Git, Python, and Docker; it is not a collection of operating-system built-in commands.
- `zh-CN/` contains Simplified Chinese pages; `en-US/` contains English pages.
- Platform-specific pages take precedence over pages with the same filename in `common`.
- If a platform-specific page is absent, the application may use the matching `common` page as a fallback. A platform-specific match is returned on its own and is not merged with the common page.
- Linux Mint, Ubuntu, and Debian share the Linux documentation directory.
- The current loader scans only top-level `*.md` files in each platform/language directory; it does not recurse into nested directories.

## Markdown page format

Each command page uses TOML Front Matter delimited by standalone `+++` lines. A page requires a non-empty `summary` and a non-empty Markdown body:

```markdown
+++
summary = "Display files and directories in the current location."
+++

## Basic syntax

Describe the command syntax and practical examples here.
```

## Integration-test sample pages

The following English pages are retained as integration-test samples, not as a complete command reference:

- `commands/windows/en-US/dir.md`: Windows-specific `dir` page.
- `commands/common/en-US/dir.md`: same-name shared fallback for checking platform precedence.
- `commands/common/en-US/git.md`: shared command page for checking common fallback.

## Contribution status

- [x] Create the knowledge-base root and version manifest.
- [x] Create command directories for common, Linux, and Windows.
- [x] Add `zh-CN` and `en-US` language directories.
- [x] Add a minimal set of English sample command pages for integration testing.
- [ ] Gradually expand and validate the command catalog.
