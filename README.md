# Rust-Bind-Shell
A multi-threaded bind shell for UNIX systems writen in Rust

# Building
```
git clone https://github.com/TheStilbruch/Rust-Bind-Shell
cd Rust-Bind-Shell
cargo build --release && strip target/release/rust-bind-shell
```

# Usage
 ./rust-bind-shell *PORT* *ADDRESS*
