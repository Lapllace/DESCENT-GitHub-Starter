# Technical architecture — proposal

**Target:** Unreal Engine 5.8. Validate during prototype.

| System | Responsibility |
|---|---|
| Player Controller | Input and commands |
| Descent Movement | Automatic downward motion |
| Lateral Shift | Column transitions and movement feedback |
| Scanner Component | Threat detection and presentation data |
| Chunk Manager | Spawn, recycle and stream nearby segments |
| Gameplay Generator | Hazards, gaps, resources and route constraints |
| Path Validator | Confirms at least one valid route |
| Environment Generator | Decorative PCG dressing |
| Roguelike Manager | Run upgrades and run state |
| Progression Manager | Persistent unlocks |
| Biome Manager | Underground strata configuration |
| Save System | Persistent progression |

## Principles
- Core deterministic gameplay rules in C++ where practical.
- Blueprints for presentation, animation, VFX, UI and tuning.
- Controlled player movement and deliberate collision handling; do not rely on free physics for the entire descent.
- Seeded generation for reproducible tests.
- Scanner detection data separate from collectible placement.
- Gameplay generation independent from decorative PCG dressing.

## Unreal collaboration
`.uasset` and `.umap` are binary. Avoid concurrent edits to the same asset. Use Git LFS and consider file locking for shared assets.
