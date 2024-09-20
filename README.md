# Stroustrup Style

This is a [Clang-Format](https://clang.llvm.org/docs/ClangFormatStyleOptions.html) file that formats C/C++ source code using the 'Stroustrup' style.

To use it, place the `.clang-format` file in the same directory as the one from which you run the **clang-format** command.

For exemple, to format all the `.cpp` files located in a directory named `src` :
```
$ clang-format -i src/*.cpp
```