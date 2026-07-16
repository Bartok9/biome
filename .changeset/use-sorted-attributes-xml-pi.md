---
"@biomejs/biome": patch
---

Fixed [`useSortedAttributes`](https://biomejs.dev/assist/actions/use-sorted-attributes/) rewriting attributes on `<?xml …?>` processing instructions, which violated the XML 1.0 fixed order (`version`, then `encoding`, then `standalone`) and could corrupt SVG/XML files. See #10922.
