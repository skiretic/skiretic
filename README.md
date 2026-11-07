# skiretic

I'm a core developer on [86Box](https://github.com/86Box/86Box), the emulator for vintage IBM PC
compatibles. Most of my work is in the CPU recompiler, video card emulation, and making 86Box run
well on Apple Silicon.

[![Sponsor on GitHub](https://img.shields.io/badge/Sponsor_on_GitHub-%E2%9D%A4-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/skiretic)
[![Donate via PayPal](https://img.shields.io/badge/Donate_via_PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/skiretic)

**If my work has been useful to you, a sponsorship or a one-time donation keeps it going. Thank you.**

## What I work on in 86Box

### Dynamic recompiler
- Speed and correctness work on the recompiler, on both arm64 and x86-64
- Compiling more of what used to fall back to the interpreter
- Keeping recompiled code exact against the interpreter, guest timing included

### CPU and FPU accuracy
- CPU and x87 behavior matched to the original manuals
- Fixes for bugs found by real guest software

### Video
- ATI Rage 128 emulation: Rage Fury Pro AGP, Xpert 128 PCI, Rage Fury MAXX
- An arm64 JIT for the 3dfx Voodoo renderer
- PGC and IM-1024 fixes (AutoCAD 2.62, VersaCAD 5.3), SVGA bus timing

### USB
- USB host controllers (UHCI, OHCI) and USB devices

### Other
- macOS and Apple Silicon support
- Machine and device fixes across the codebase
