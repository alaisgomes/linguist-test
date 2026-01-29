# Linguist Detection Test Codebase

Test suite to evaluate GitHub Linguist's language detection capabilities across various edge cases.

## Structure

- **standard/** - Control group with standard file extensions
- **no-extension/** - Files without extensions (shebang/content-based detection)
- **wrong-extension/** - Misleading file extensions
- **shebang-only/** - Files relying on shebang detection
- **cobol-variants/** - COBOL with various extensions (.cbl, .cob, .cpy, .pco, .txt)

## Purpose

Tests what Linguist detects vs. misses when analyzing language statistics.
