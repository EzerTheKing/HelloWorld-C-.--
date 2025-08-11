# Hello guys.! l.m presetn my Hello World C.!

## Install bazel compiler + clang/gcc:

Official web site Download (Windows): https://bazel.build/

```
Official web site Download (Linux):
*Arch: sudo pacman -S bazel gcc clang

*Artix: sudo pacman -S bazel gcc clang

*Debian/Ubuntu: sudo apt update | sudo apt install build-essential

*NixOS: environment.systemPackages = with pkgs; [
    bazel
    gcc
    clang
  ];
```

## Git Copy Repo the PC:
```
git clone https://github.com/EzerTheKing/HelloWorld-C-.--.git
```
## Build Code:
```
bazel query "//:*"

bazel build //...
```
## Result:
```
cd bazel-bin

./hello_world_c

HelloWorld-C.!
```
