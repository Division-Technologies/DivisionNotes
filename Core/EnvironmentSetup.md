# C++開発環境構築
この記事では、C++の開発環境を構築するための基本的な手順を説明する。

事前に読む：[C++開発環境](./Environment.md)


## Windows
`winget` を使って必要なツールをインストールします。
```powershell
winget install LLVM.LLVM
winget install LLVM.clangd
winget install Kitware.CMake
winget install Ninja-build.Ninja
winget install Cppcheck.Cppcheck

winget install Microsoft.VisualStudio.BuildTools --override "--wait --passive --config ./buildtools.vsconfig"

# cmake --preset clang-debug && cmake --build --preset clang-debug

```

### Editor
Visual Studio Code をインストールし、C++開発に必要な拡張機能を追加します。
- [CMake Tools (Microsoft)](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cmake-tools)
- [Clangd (LLVM)](https://marketplace.visualstudio.com/items?itemName=llvm-vs-code-extensions.vscode-clangd)
