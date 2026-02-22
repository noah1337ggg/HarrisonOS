# HarrisonOS

> A modern open-source operating system built in C, Rust and Assembly.  
> Lightweight by design. Secure by architecture. Powerful by intent.

---

## Overview

HarrisonOS is a low-level operating system focused on performance, memory safety, and precise hardware control.  
It is designed with clarity, modularity, and long-term maintainability in mind.

The project combines:

- **C** for core system control
- **Rust** for memory-safe components
- **Assembly** for architecture-specific routines

HarrisonOS aims to provide a clean and structured foundation for building a modern kernel without unnecessary complexity.

---

## Design Principles

- Clarity over cleverness
- Strict separation of architecture-dependent code
- Minimalism with purpose
- Security-first mindset
- Deterministic and predictable behavior

No legacy baggage. No unnecessary abstractions. No chaos.

---
## Current Status

🚧 Early development stage.

Planned milestones:

- [ ] Bootloader initialization
- [ ] Enter long mode (x86_64)
- [ ] Basic memory management
- [ ] Interrupt Descriptor Table (IDT)
- [ ] Minimal scheduler
- [ ] Basic driver layer

---

## Build (Planned)

Build instructions will be provided as the toolchain stabilizes.

Expected toolchain:

- GCC or Clang
- Rust (nightly if required)
- NASM or GAS
- QEMU for virtualization testing

---

## License

Licensed under the MIT License.  
See the `LICENSE` file for details.

---

## Vision

HarrisonOS is not just an experiment.  
It is a disciplined attempt to build a structured, modern operating system from the ground up.
