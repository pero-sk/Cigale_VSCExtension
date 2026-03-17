# Changelog

All notable changes to the Cigale extension will be documented here.

## [0.0.1] - 2026-03-16

### Added
- Syntax highlighting for `.cig` files
    - Keywords, declarations, types, modifiers
    - String interpolation (`$"..."`)
    - Multiline strings (`"""..."""`)
    - Block comments (`/" ... "/"`)
    - Numbers with `f`/`d` suffix
- Bracket matching and auto-closing
- Auto-indentation inside `{}` blocks
- Snippets for common patterns
    - `main`, `func`, `funcb`, `funci`
    - `class`, `classi`, `classof`, `inst`
    - `if`, `ife`, `for`, `foreach`, `while`, `match`
    - `import`, `importconsole`, `importerr`, `importio`
    - `resultcheck`, `var`, `static`

## [0.0.2] - 2026-03-17

### Added
- Syntax highlighting for `.cig` files
    - Type: ref\<T>