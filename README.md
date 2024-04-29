# Rust Axum

## Observe and Run changes in src folder

```shell
cargo watch -q -c -w src/ -x run
```

## Observe and Run changes in tests folder

```shell
cargo watch -q -c -w tests/ -x "test -q quick_dev -- --nocapture"
```
