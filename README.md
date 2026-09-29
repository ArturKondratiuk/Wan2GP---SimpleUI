# Wan2GP - SimpleUI

A simplified and redesigned UI for **WanGP**, inspired by Stable Diffusion WebUI.

## About

This project focuses on improving the WanGP interface:

* Removes unnecessary UI elements (for me)
* Simplifies navigation and workflow
* Provides a cleaner, modern visual design

**The WanGP backend is not rewritten.** Generation, models, queue management, LoRA processing, CUDA/VRAM handling, and existing callbacks remain part of the original WanGP system. Theoretically, you can return all the elements that I removed, since they remained in the backend.

## Installation

This project is intended for an existing WanGP installation.

Back up the original:

```text
app/wgp.py
```

Then replace it with the modified `wgp.py`.

## Important

Updating WanGP may overwrite the modified `wgp.py`. Keep a backup before updating.

## Status

Done.

## Credits

Based on **WanGP by DeepBeepMeep**.
