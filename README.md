# Yeloori
Sanskrit Programming Language

# Yeloori (यलूूरि) 🕉️

Yeloori is an advanced, production-capable, Sanskrit-inspired object-oriented programming language. Built entirely from scratch with a custom lexical tokenizer, a recursive descent parser, an Abstract Syntax Tree (AST) framework, and a tree-walking runtime environment, Yeloori marries classical linguistic precision with modern execution logic.

It features full lexical scoping, powerful control flows, exception handling (`LooriDosha`), class inheritance, and experimental asynchronous task execution.

---

## Key Features

* **Sanskrit-Based Syntax:** Lexical analysis mapped tightly to precise logical terms (e.g., `chara`, `satya`, `karma`).
* **Robust Type System:** Built-in tracking for Integers, Floats, Strings, Booleans (`satya`/`asatya`), and `shoonya` (null).
* **Object-Oriented Paradigm:** Native support for classes (`varga`), constructors, methods, and dynamic property assignment.
* **Granular Error Reporting:** Deep stack tracking through custom `LooriDosha` definitions to catch syntax, parsing, and runtime abnormalities instantly.

---

## 🛠️ Code Blueprint & Syntax Guide

Here is a glimpse of how clean and expressive coding in Yeloori looks:

### 1. Variables & Basic Output
```sanskrit
chara pratham = 10;
sthira sandesh = "Namaste, World!";

likha(sandesh);

### 2. Conditionals (yadi / anyatha)

Code snippet
chara anka = 45;

yadi (anka > 50) {
    likha("Greater than 50");
} athava (anka == 45) {
    likha("Exactly 45");
} anyatha {
    likha("Less than 45");
}
### 3. Functions (karma) & Loops (yaavat)

Code snippet
karma gannana(n) {
    chara ganana = 1;
    yaavat (n > 0) {
        ganana = ganana * n;
        n = n - 1;
    }
    pratyavartaya ganana;
}

chara parinama = gannana(5); // Returns 120
likha(parinama);
# Installation & Setup
Since Yeloori's runtime engine is encapsulated globally, you can clone and execute scripts instantly using the command-line interface.

Prerequisites

Python 3.8 or higher

Local Clone & Launch

Bash
# 1. Clone your project structure
git clone [https://github.com/yelooripooja/Yeloori.git](https://github.com/yelooripooja/Yeloori.git)
cd Yeloori

# 2. Run an example script via the interpreter
python cli/main.py examples/shanti.loori
Repository Architecture
The project structure is organized according to professional language design distributions:

Plaintext
├── sansthrutha/
│   ├── core/
│   │   ├── engine.py          # Lexer, Tokenizer, Parser, & Interpreter Core
│   │   └── __init__.py
│   ├── runtime/               # Environment variable framing scopes
│   ├── stdlib/                # Built-in methods and system utilities
│   └── ai/                    # Experimental compiler logic enhancements
├── cli/
│   └── main.py                # Command Line Application Interface Entry point
├── vscode-extension/         # Syntax highlighting schemas for VS Code
├── tests/                     # Unit and integration validation suites
└── examples/                  # Sample script files (.loori)
Future Roadmap
[ ] Complete full compilation release to the PyPI Package Index (pip install yeloori).

[ ] Publish the native VS Code Extension to the Visual Studio Marketplace for syntax highlighting.

[ ] Build an interactive, web-based WebAssembly (WASM) compiler playground to run Yeloori code straight from a web browser.

Contributing & Community
Contributions to the Yeloori Engine are highly encouraged! If you want to optimize parser performance, expand the standard library bindings, or implement more expressive grammar tokens:

Fork the Project.

Create your Feature Branch (git checkout -b feature/SanskritEnhancement).

Commit your Changes (git commit -m 'Add support for unique math operators').

Push to the Branch (git push origin feature/SanskritEnhancement).

Open a Pull Request.

Author: Yeloori Pooja

License: Distributed under the MIT License.


---

### Pro-Tip for your GitHub Profile:
Since your GitHub path has capitalization in the repository name (`Yeloori` vs `yeloori`), double-check that your terminal commands match exactly when running your git setups. 

Would you like to write a quick syntax definitions file (`yeloori.tmLanguage.json`) next so that your VS Code extension folder is ready to give code editors beautiful colors for your keywords?
