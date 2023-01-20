# HellOS
I have made changes for the last two versions of ZIG because each version requires a small rewrite in the code. The master branch has remained untouched since version 0.7.1. Check out the branches!

Bare bones "hello world" i386 kernel written in [Zig](https://ziglang.org/) version 0.11.0-dev.

## Building

```
zig build-exe hellos.zig -target x86-freestanding -T linker.ld
```

## Testing with qemu

```
qemu-system-i386 -kernel hellos
```
