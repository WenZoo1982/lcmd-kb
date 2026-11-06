+++
summary = "Display and manage IP configuration for network adapters."
+++
---

## Purpose

Display and manage IP configuration for network adapters.

## Syntax

```cmd
ipconfig [options]
```

## Common options

/all show detailed configuration; /flushdns clear DNS cache; /release release DHCP address; /renew renew the address.

## Examples

```cmd
ipconfig /all
```

## Usage notes

Command type: Windows networking utility. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `ipconfig /?` to see the full syntax and options available on the current Windows version.
