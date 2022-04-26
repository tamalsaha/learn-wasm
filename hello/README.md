# hello

```
> tinygo build -o wasm.wasm -target wasm ./main.go
> wasm-opt wasm.wasm -Oz -o opt2.wasm

> ls -l
total 4404
-rw-r--r-- 1 tamal staff      80 Apr 26 13:33 main.go
-rwxr-xr-x 1 tamal staff 2006669 Apr 26 13:33 main.wasm*
-rw-r--r-- 1 tamal staff 1911460 Apr 26 13:56 opt.wasm
-rw-r--r-- 1 tamal staff  262322 Apr 26 14:39 opt2.wasm
-rwxr-xr-x 1 tamal staff  315845 Apr 26 14:38 wasm.wasm*
```
