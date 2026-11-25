# Project structure

This document describes the repository layout.

```
RetroWowUpdateResp/
+- README.md          # Project overview, getting started, and usage
+- docs/              # Detailed documentation
|   +- usage.md       # How to create and push update responses
|   +- getting-started.md  # First steps and prerequisites
|   +- project-structure.md  # This file
+- example/           # Example files with inline comments
|   +- README.md      # Description of the example files
|   +- sample-update.txt     # Sample update response
+- package.json       # Node manifest
+- LICENSE            # MIT license text
+- .gitignore         # Files and folders ignored by git
```

## Conventions

- Keep all user-facing text in English.
- Do not use emojis in commit messages or file content; this is a public
  repository.
- Use conventional commit prefixes such as docs:, feat:, fix:, chore:.
- Document any new folder with a short README.md inside it.
- Do not commit real credentials or secrets.
