## Build and run locally

After cloning the repository, run:

```bash
rustup toolchain install 1.89.0
rustup override set 1.89.0

# pull deps and build only anvil and cast
cargo update
cargo build --release -p anvil -p cast
```

Usage:

- anvil: `target/release/anvil`
- cast: `target/release/cast`


