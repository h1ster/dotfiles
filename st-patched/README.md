# st-patched

Minimal terminal emulator based on suckless `st` with applied patches.

---

## Description

This is a patched build of `st` (suckless terminal) that includes multiple usability improvements while preserving the original minimal and suckless philosophy.

All patches are directly integrated into the source tree.

---

## Features / Patches

- alpha  
  → background transparency support (requires X11 compositor)

- scroll  
  → mouse wheel scrolling in terminal buffer

- drag-n-drop  
  → support for dragging files from a file manager (e.g. Thunar) into the terminal, inserting file paths

---

## Installation

Build and install from source:

```bash id="g1m8s9"
git clone https://github.com/tinyopsec/st-patched
cd st-patched
sudo make clean install
