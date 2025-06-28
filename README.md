# DropCatch-BucketGame (8086 Assembly Language)

## Overview

DropCatch-BucketGame is a simple graphical game developed using 8086 Assembly Language where the player controls a bucket at the bottom of the screen to catch falling drops. The objective is to catch as many drops as possible and avoid missing them. It demonstrates direct interaction with low-level graphics, keyboard input, and game logic using Assembly.

---

## Gameplay

- Drops (pixels/blocks) fall from the top of the screen at regular intervals.
- The player moves the bucket **left** or **right** using **arrow keys**.
- Catching a drop increases the score.
- Missing a drop might reduce lives or end the game depending on settings.

---

## Requirements

- **Emulator**: DOSBox / EMU8086 / TASM
- **Platform**: MS-DOS environment
- **Assembler**: TASM or any compatible assembler that supports x86 16-bit

---

## How to Run

1. Open the project in **EMU8086** or **TASM**.
2. Assemble the `.asm` file:
   ```bash
   tasm DiamondDrop.asm
   tlink DiamondDrop.obj
   DiamondDrop.exe
