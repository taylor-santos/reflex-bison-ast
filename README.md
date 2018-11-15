# reflex-bison-ast

Cloned from https://github.com/UO-cis561/reflex-bison-ast. Modified to parse Quack (.qk) source code. 
Successfully parsed code will be assembled into an abstract syntax tree (AST). Then, type checking occurs to infer the types of all methods and variables as well as find type errors. A list is printed of all classes, with each method listed with inferred return type and types of all variables used. Any variables used in the program body are then printed with their inferred types.

## Building
Run the following commands from the project's root directory:
```
mkdir cmake-build-debug
cd cmake-build-debug
cmake -DCMAKE_BUILD_TYPE=Debug ..
make
```
