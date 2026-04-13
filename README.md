# Rust Programming Language — Source Code Repository

**Book:** Rust Programming Language: A Complete Beginner's Guide  
**Edition:** First Edition | Updated through March 2026  
**Compiler:** Rust 1.85.0 (Edition 2021)  
**Repository:** https://github.com/ey11gen/rust-programming-codes

---

## How to Use This Repository

Every code example, worked illustration, and exercise from all 20 chapters is
collected here. Files are organized by chapter. Each file is self-contained and
can be compiled and run independently with the Rust toolchain.

### Running a file

```bash
rustc filename.rs -o output && ./output
```

Or copy the file into a Cargo project:

```bash
cargo new my_project
cp filename.rs my_project/src/main.rs
cd my_project && cargo run
```

### Prerequisites

Install Rust via rustup (https://rustup.rs):

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Verify installation:

```bash
rustc --version   # rustc 1.85.0
cargo --version   # cargo 1.85.0
```

---

## Repository Structure

```
rust-programming-codes/
├── README.md
├── Chapter_01/   Getting Started with Rust
├── Chapter_02/   Variables, Data Types, and Constants
├── Chapter_03/   Control Flow
├── Chapter_04/   Functions
├── Chapter_05/   Comments and Documentation
├── Chapter_06/   Understanding Ownership
├── Chapter_07/   Borrowing and References
├── Chapter_08/   The Slice Type
├── Chapter_09/   Lifetimes
├── Chapter_10/   Structs
├── Chapter_11/   Methods and Associated Functions
├── Chapter_12/   Enums and Pattern Matching
├── Chapter_13/   Common Collections
├── Chapter_14/   Error Handling
├── Chapter_15/   Organizing Code with Modules
├── Chapter_16/   Generics
├── Chapter_17/   Traits
├── Chapter_18/   Advanced Types and Type Aliases
├── Chapter_19/   Smart Pointers
└── Chapter_20/   Iterators
```

---

## License

All code in this repository is provided for educational purposes.
You are free to use, modify, and distribute it for personal and
commercial projects. Attribution appreciated but not required.

---

*Happy coding — and welcome to Rust!*
