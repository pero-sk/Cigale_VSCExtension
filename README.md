# Cigale Language Support

Visual Studio Code extension for the [Cigale](https://github.com/pero-sk/cigale) programming language.

## Features

### Syntax Highlighting

Full syntax highlighting for `.cig` files including:

- Keywords (`if`, `else`, `for`, `foreach`, `while`, `match`, `return`, etc.)
- Declarations (`func`, `class`, `inst`, `of`, `import`, `static`)
- Types (`int`, `float`, `double`, `str`, `bool`, `list`, `result`)
- Access modifiers (`public`, `private`, `protected`, `blank`, `impl`)
- Constants (`true`, `false`, `null`)
- Numbers (integers, floats with `f`/`d` suffix)
- Strings including interpolated strings (`$"hello {name}"`)
- Multiline strings (`"""..."""`)
- Single line comments (`//`)
- Block comments (`/" ... "/`)

### Snippets

| Prefix | Description |
|---|---|
| `main` | Entry point function |
| `func` | Function declaration |
| `funcb` | Blank function declaration |
| `funci` | Impl function declaration |
| `class` | Sealed class declaration |
| `classi` | Instantiable class declaration |
| `classof` | Inheriting class declaration |
| `inst` | Enum declaration |
| `if` | If statement |
| `ife` | If else statement |
| `for` | For loop |
| `foreach` | Foreach loop |
| `while` | While loop |
| `match` | Match statement |
| `import` | Import statement |
| `importconsole` | Import stdl.console |
| `importerr` | Import stdl.err |
| `importio` | Import stdl.io |
| `resultcheck` | Result error check pattern |
| `var` | Variable declaration |
| `static` | Static block |

### Bracket Matching

Auto-closes and matches `{}`, `[]`, `()`, `""`.

### Indentation

Auto-indents inside `{}` blocks.

---

## Installation

### From Marketplace
Search for `Cigale` in the VSCode Extensions marketplace.

### From Source
```bash
git clone https://github.com/pero-sk/cigale-vscode
cd cigale-vscode
npm install
npx vsce package
code --install-extension cigale-0.0.1.vsix
```

---

## Cigale

Cigale is a statically-typed interpreted programming language built in Rust.

```
import stdl.console { cout };

func public static main() {
    cout("Hello, world!");
}
```

- [Cigale repository](https://github.com/pero-sk/cigale)
- [Install Cigale](https://github.com/pero-sk/cigale#install)

---

## License

[MIT](https://raw.githubusercontent.com/pero-sk/Cigale_VSCExtension/refs/heads/main/LICENSE)