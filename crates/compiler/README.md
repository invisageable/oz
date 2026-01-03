# crates — compiler — oz.

> _a compiler for the oz configuration file format_.

THE `.oz` FORMAT iS CLEAN, DECLARATiVE, AND PARSED BY A ZERO-ALLOCATiON HAND-WRiTTEN PARSER:

```oz
-- project configuration.

@pack = (
  name: "my-project",
  version: "0.1.0",
  authors: ["invisageable <you@example.com>"],
  license: "MIT OR Apache-2.0",
)
```
