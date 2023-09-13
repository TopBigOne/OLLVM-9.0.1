
* step 1
```shell
mkdir build && cd build
```

* step 2
```shell
cd build && cmake -DCMAKE_BUILD_TYPE=Release -DLLVM_CREATE_XCODE_TOOLCHAIN=ON ../
```


* step 3
```shell
cd build && make -j16
```
