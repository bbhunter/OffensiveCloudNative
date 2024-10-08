# Cross-compiling Go binaries

**Description:** This entry describes how to cross-compile Go binaries

**Requirements:** go

```
env GOOS=linux GOARCH=amd64 go build code.go
```

Cross-compile go code for Linux x86_64.

```
env GOOS=linux GOARCH=arm GOARM=6 go build code.go
```

Cross-compile go code for Linux ARM-specific CPU (6/7).

See References for more OS and Target platform types.

## References
* [How To Build Go Executables for Multiple Platforms on Ubuntu 20.04](https://www.digitalocean.com/community/tutorials/how-to-build-go-executables-for-multiple-platforms-on-ubuntu-20-04)
