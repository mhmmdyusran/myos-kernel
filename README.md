# MY OS Kernel

MY OS Kernel is a 64-bit monolithic kernel written from scratch
as the core of **MY OS (Muhammad Yusran Operating System)**.

This repository contains **only the kernel**.
Userland, shell, and system utilities will live in a separate repository.

---

## 🎯 Project Goals

- Build a modern **x86_64 kernel** from zero
- Understand kernel internals deeply (boot, memory, scheduler)
- Maintain a **clean, structured, and professional codebase**
- Serve as a long-term educational and experimental kernel project

---

## 🧠 Kernel Design

- **Architecture:** x86_64 (Long Mode)
- **Kernel Type:** Monolithic
- **Bootloader:** GRUB (Multiboot2)
- **Languages:** C and Assembly
- **Standard Library:** None (freestanding)
- **Debugging:** QEMU + GDB

---

## 📁 Repository Structure

myos-kernel/
├── arch/ # Architecture-specific code
│ └── x86_64/
├── core/ # Kernel core logic
├── drivers/ # Hardware drivers
├── include/ # Public kernel headers
├── scripts/ # Build & helper scripts
├── docs/ # Design & roadmap documentation
├── build/ # Build output (gitignored)
├── Makefile
├── README.md
├── CHANGELOG.md
└── LICENSE

---

## 🛠 Build Status

> ⚠️ **Work in Progress**

Current release: **v0.0.1 (Genesis)**

This release initializes:

- Repository structure
- Documentation
- Versioning and development workflow

The kernel is **not bootable yet**.

---

## 🧭 Roadmap Overview

- **0.1.0** — Bootable kernel (GRUB + VGA text output)
- **0.2.0** — CPU & interrupt handling (GDT, IDT, ISR)
- **0.3.0** — Memory management (paging, heap)
- **0.4.0** — Scheduler & multitasking
- **0.5.0** — System call interface
- **1.0.0** — Stable kernel core

See `docs/ROADMAP.md` for full details.

---

## 📜 Versioning

This project follows **Semantic Versioning**:

MAJOR.MINOR.PATCH

- **MAJOR:** Breaking architectural changes
- **MINOR:** New kernel subsystems
- **PATCH:** Bug fixes and refactors

---

## 📄 License

MIT License

Copyright (c) 2026  
Muhammad Yusran
