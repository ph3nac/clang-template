# This is a template for clang development using brew llvm/clang, Cmake ,vscode

# usage
Call `Cmake: Edit User Local Cmake Kit` to open cmake-tools-kit.json

and add below in cmake-tools-kits.json
```jsonc
{
  {
    "name": "brew clang",
    "compilers":{
      "C":"<path to your llvm/bin/clang>",
      "CXX":"<path to your llvm/bin/clang++>"
    }
  }
}
```
