```
> mkdir thirdparty
> cd thirdparty
> git submodule add https://github.com/llvm/llvm-project.git

> cd llvm-project
> mkdir build
> cmake -G Ninja -DCMAKE_BUILD_TYPE=Release -DLLVM_ENABLE_PROJECTS='mlir' ../llvm
> ninja -j8
```