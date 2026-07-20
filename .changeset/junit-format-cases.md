---
"@biomejs/biome": patch
---

Fixed `#5172`: the JUnit reporter now emits test cases for formatter diagnostics that have a file path but no source span (previously `tests="0"` while `errors` was non-zero).
