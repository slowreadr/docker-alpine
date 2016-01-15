Erlang/OTP on Alpine Linux
=====

Erlang/OTP minimal environment.

Latest version: **18.1**
Image size: **18.3 MB**

The following packages are pre-installed:

- ncurses-libs
- erlang-kernel
- erlang-stdlib
- erlang-compiler
- erlang

> **Notice:** In order to keep images as compact as possible, Erlang libraries for Alpine Linux are split into many different packages. The full list of Erlang packages available can be found [here](https://pkgs.alpinelinux.org/packages?name=erlang%25&repo=all&arch=x86_64&maintainer=all)

## Usage

```
$ docker run --rm -it slowreadr /erlang erl
Erlang/OTP 18 [erts-7.1] [source] [64-bit] [smp:4:4] [async-threads:10] [kernel-poll:false]

Eshell V7.1  (abort with ^G)
1> io:fwrite("Hello, world!\n").
Hello, world!
ok
2>
```
