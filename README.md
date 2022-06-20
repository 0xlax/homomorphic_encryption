# homomorphic_encryption

Motivation : [Homomorphic Encryption](https://humanata.com/blog/illustrated_primer/)

References
* [Microsoft SEAL](https://github.com/microsoft/SEAL)
* [Lttigo](https://github.com/ldsec/lattigo)
* [DEMO](https://github.com/microsoft/SEAL-Demo)
* [SEAL Example](https://github.com/microsoft/SEAL/issues/206)

Setup:


[homomorphic](https://humanata.com/images/blog/aheip/thumbnail.png)


Compile wasm library from ```server/static/wasm/wasm_exec.js```

```cp $GOROOT/misc/wasm/wasm_exec.js html/wasm_exec.js```
 
 ```GOOS=js GOARCH=wasm go build -o  server/static/wasm/main.wasm  main.go ```


### Server
cd into the server dir and run ```server.go```

```go run server.go```

go to [http://localhost:8080/static/](http://localhost:8080/static/)

