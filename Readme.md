# WebAssembly Simple Sample

```
$ git clone git@github.com:tkihira/wasm-simple-sample.git
$ cd wasm-simple-sample
$ python -m SimpleHTTPServer 8888 &
$ open http://localhost:8888/simple.html
```

## How to build .wasm file

1. Install `wat2wasm` from https://github.com/webassembly/wabt
2. wat2wasm -o simple.wasm simple.wast

## License

MIT License

