# HellOS

Bare bones "hello world" i386 kernel written in [Zig](https://ziglang.org/).

## Building

```
zig build-exe hellos.zig -target i386-freestanding --linker-script linker.ld
```

## Testing with qemu

```
qemu-system-i386 -kernel hellos
```
