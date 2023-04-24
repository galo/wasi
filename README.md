# wasi


1. install [TinyGo](https://tinygo.org/getting-started/install/linux/)

2. build wasm file

```shell
tinygo build  -target=wasi -o main.wasm main.go
```

3. run wasm file

```shell
wasmtime --dir . main.wasm
```
