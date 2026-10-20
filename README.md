# Home Device Simulation

Interactive simulation exploring whether a single home AI device can answer its own sensors and devices quietly — comparing traditional Von Neumann/GPU architectures (weights hauled on every token) versus Compute-in-Memory (weights stay in place).

## View the simulation

Open [index.html](https://github.com/akshayking517/home-device-simulation/blob/main/index.html) or enable GitHub Pages (Settings → Pages → Source: Deploy from a branch → main / root) to host it live at:

https://akshayking517.github.io/home-device-simulation/

## How it works

- Switch between Standard Chip (GPU) and In-Memory Chip modes.
- Slide or click presets for model sizes from 80M (voice switches) to 100B (world engine).
- Watch power draw, surface temperature, wire traffic, and whether a fan is needed.
- Run a 1,000-day weather simulation to estimate fan risk.

The physics model approximates data movement energy for 4-bit weights at 100 tokens/second against an 18 W passive cooling limit for a small sealed box.
