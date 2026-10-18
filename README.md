# Bash Workflow

Documentation for developing, testing, installing, and maintaining Bash scripts on Ubuntu.

## Purpose

This repository documents a consistent workflow for managing personal Bash utilities.

The workflow separates editable source code from installed executable commands.

## Environment

- **Operating system:** Ubuntu 24.04
- **Source directory:** `~/Desktop/projects/bash/`
- **Installation directory:** `/usr/local/bin/`
- **Shell:** Bash
- **Installer:** `install-bash-script`

## Workflow

1. Create a project directory containing the executable source file and a `README.md`.
2. Check the script syntax using `bash -n`.
3. Test the script locally.
4. Install or update it using `install-bash-script`.
5. Verify the installed command using `command -v`.

The source file does not need execute permissions when installed through `install-bash-script`, because the installer uses `install -m 755`.

## Documentation

- [Script Development Workflow](docs/script-development-workflow.uk.md) — complete instructions, examples, troubleshooting, updates, and removal.

## Related Projects

- `install-bash-script` — installs Bash scripts into `/usr/local/bin/`.
- `linux-mood` — a small terminal entertainment utility.
- `count-pdf-pages` — a utility for counting PDF pages.

Add repository links here when the corresponding GitHub repositories are available.

## Maintenance

Update this documentation whenever the workflow or installer behavior changes.
