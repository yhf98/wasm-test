#  WebAssembly 初探

## 编译
```
emcc math.c -Os -s WASM=1 -s SIDE_MODULE=1 -o math.wasm
```

## 运行
```
npm i live-server -g

npm run dev
```