# HellOS

Bare bones "hello world" i386 kernel written in [Zig](https://ziglang.org/) version 0.10.1.

## Building

```
zig build-exe hellos.zig -target i386-freestanding -T linker.ld
```

## Testing with qemu

```
qemu-system-i386 -kernel hellos
```
