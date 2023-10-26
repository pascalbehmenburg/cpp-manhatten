# manhatten-project-extensions

## Extensions provided

- **clangd** will be used for code completion, compile errors / warnings, symbol search, hover/inlay hints, code formatting and refactoring
 - note: when installed the first time it might prompt you to install clang compiler, please do so, otherwise you won't be able to use the extension properly. If you did not react to the prompt, see install instructions for [clang compiler](https://clang.llvm.org).
 - also clangd will auto insert `#include` headers automatically by default which might cause issues if you've meant to reference something different than clangd might suggest therefore you might want to disable this feature if it causes issues. To do this navigate to the extension settings and edit the `Clangd: Arguments` to include `-header-insertion=never`.
- **CodeLLDB** is used as a debugger
- **CMake Tools** provides support for using cmake build tools, create projects, interact with cmake in other not yet know ways :D (includes CMake language extension)
- **GitLens** provides git integration (also note Alt + B to toggle git blame :sunglasses: )
- **Test Explorer UI** adds testing ui (requires Test Adapter Converter)
