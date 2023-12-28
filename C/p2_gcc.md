# C源文件->预处理->编译->汇编->链接->可执行文件

完整过程:
预处理：

```shell
gcc -E hello.c > hello.i
```

* 编译：

```shell
gcc -S hello.i 
```

* 汇编：

```shell
gcc -c hello.s 
```

* 链接->可执行文件

```shell
gcc hello.o -o hello
```

或者：

```shell
gcc hello.c -o hello
```

```shell
make hello
// 没有后缀
```
