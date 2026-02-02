# MY OS Kernel Architecture

## Design

- Monolithic kernel
- Modular internal subsystems
- Architecture-dependent code isolated in /arch

## Layers

- arch/ → CPU & platform specific
- core/ → Kernel core logic
- drivers/ → Hardware drivers
- include/ → Public kernel headers

## Build

- Custom linker script
- No libc
- No dynamic linking
