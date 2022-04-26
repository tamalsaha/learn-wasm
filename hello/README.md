# hello

```
> tinygo build -o wasm.wasm -target wasm ./main.go
> wasm-opt wasm.wasm -Oz -o opt2.wasm
> wasm2js opt2.wasm -Oz > opt2.js

> ls -l
total 6068
-rw-r--r-- 1 tamal staff     439 Apr 26 15:29 README.md
-rw-r--r-- 1 tamal staff      80 Apr 26 13:33 main.go
-rw-r--r-- 1 tamal staff  934096 Apr 26 15:14 main.js
-rw-r--r-- 1 tamal staff   54184 Apr 26 15:14 main.js.map
-rwxr-xr-x 1 tamal staff 2006669 Apr 26 13:33 main.wasm*
-rw-r--r-- 1 tamal staff 1911460 Apr 26 13:56 opt.wasm
-rw-r--r-- 1 tamal staff  611962 Apr 26 15:28 opt2.js
-rw-r--r-- 1 tamal staff  262322 Apr 26 14:39 opt2.wasm
-rwxr-xr-x 1 tamal staff  315845 Apr 26 14:38 wasm.wasm*
```
