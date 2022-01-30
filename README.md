run 
```
matchbox_server
```
in one terminal

and 

```
cargo install wasm-server-runner

cargo watch -cx "run --release --target wasm32-unknown-unknown"
```

in another.