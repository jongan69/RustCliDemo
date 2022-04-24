# Rust/Cargo CLI Tool
Version: 1.0.0
This tool is being buit using Rust CLI tool book: 
https://rust-cli.github.io/book/tutorial/impl-draft.html

# Goals
- Allow arguments to be passed with files
- Using selected files and arguments return a specific output

# Usage
To build and run this tool you must have rust + Cargo installed
``
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
``
Once Rust is installed you may run: 
``
cargo run -- Welcome README.md
``
The line below this will print
# Welcome to the RUST CLI Tool V1

This takes a file passed in with argument(s) and returns data based on the inputs arguments, in this case being 'Welcome' and 'Readme.md'

