---
"@biomejs/biome": patch
---

Fixed #9105: `vcs.useIgnoreFile` now ignores files under ignored directories for full paths, and nested `.gitignore` negation patterns correctly override parent rules.
