# HellOS

Bare bones "hello world" i386 kernel written in [Zig](https://ziglang.org/).

## Building

```
zig build-exe hellos.zig --target-os freestanding --target-arch i386 --static  --linker-script linker.ld
```

## Testing with qemu

```
qemu-system-i386 -kernel hellos
```
