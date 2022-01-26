# HellOS

Bare bones "hello world" i386 kernel written in [Zig](https://ziglang.org/).

[Video of me live coding it](https://vimeo.com/483928663).

## Building

```
zig build-exe hellos.zig -target i386-freestanding -T linker.ld
```

## Testing with qemu

```
qemu-system-i386 -kernel hellos
```
