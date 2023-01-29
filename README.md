### Main file is stored in `bin/` directory
### Other utility 'files / libs' are stored in `lib/` directory
### All test files are stored in `test/` directory

### To run the program, type the following command in the terminal

```
dart run
```

### To run the tests, type the following command in the terminal

```
dart test
```

---

### In Dart, all dependencies are stored in `pubspec.yaml` file
### In Dart, dependencies are called as `packages`

### A package which is not posted on pub.dev is called as 'application package'

### A package which is posted on pub.dev is called as 'library package'

### To install the dependencies, type the following command in the terminal

```
pub get
```

### When using a library package, we only have access to libraries and files which are exported by the package and not the internal files

### to run a particular test file, type the following command in the terminal

```
dart test test/<file_name>.dart
```

### To run a particular test group, type the following command in the terminal

```
dart test test/<file_name>.dart -g <group_name>
```

### To run a particular test case, type the following command in the terminal

```
dart test test/<file_name>.dart -n <test_name>
```

### To run a particular dart file, type the following command in the terminal

```
dart <file_name>.dart
```

### To run a particular dart file with arguments, type the following command in the terminal

```
dart <file_name>.dart <arg1> <arg2> <arg3> ...
```

### Use devtools to debug the code

### install devtools using the following command

```
pub global activate devtools
```

### To run devtools, type the following command in the terminal

```
devtools
```

### To run devtools on a particular port, type the following command in the terminal

```
devtools --port <port_number>
```

### Run dart project with devtools using the following command

```
 dart run --observe --pause-isolates-on-start
```

### running code from source using JIT compiler

```
dart compile kernel <file_path>.dart
dart run <file_path>.dll
```

### running code from source using AOT compiler

```
dart compile exe <file_path>.dart
dart run <file_path>.exe
```

### to time the execution of a program, use the following command

```
Measure-Command { dart run }
```

### creating a jit-snapshot

```
dart compile jit-snapshot <file_path>.dart
dart run <file_path>.jit
```

### creating a aot-snapshot

```
dart compile aot-snapshot <file_path>.dart
dartaotruntime run <file_path>.aot
```