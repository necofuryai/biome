---
"@biomejs/biome": patch
---

Fixed type inference for calls with `const` type parameters. Biome now preserves literal types and infers readonly tuples for inline array arguments, including their element types in indexed-access types such as `(typeof result)[number]`.
