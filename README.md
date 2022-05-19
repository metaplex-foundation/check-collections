# Check Collections

[Install Rust[(https://www.rust-lang.org/learn/get-started) v1.58 or later.

Build:

```
cargo build --release
```

or install:

```
cargo install --path ./
```

Run:

```
check-collections /path/to/mint_list.json
```

This creates a JSON file on the output showing each collection and what items are in it.

The script requires a RPC node set in your Solana config file.
