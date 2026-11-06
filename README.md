<div align="center">

# ⛏️ DESCENT
### A vertical descent. Endless decisions.

**A 3D endless runner with roguelite progression, threat-scanning and fluid lateral traversal.**

![Status](https://img.shields.io/badge/status-pre--production-orange)
![Engine](https://img.shields.io/badge/Unreal%20Engine-5.8-313131?logo=unrealengine)
![Language](https://img.shields.io/badge/C%2B%2B-Blueprints-blue)

*Descend. Read the terrain. Choose your path. Survive what lies below.*

</div>

---

## 🌌 About DESCENT

DESCENT is a 3D vertical endless runner with roguelite progression. The player continuously descends through an ever-changing underground world, shifts laterally between traversable columns, reads threats ahead and makes split-second decisions.

**The scanner is a survival instrument — not a treasure detector.**

## 🎮 Core pillars

| Pillar | Direction |
|---|---|
| Continuous descent | The character keeps moving downward; the player focuses on decisions. |
| Lateral traversal | Shift between adjacent logical columns without losing downward momentum. |
| Threat-only scanner | Reveals relevant hazards. Safe areas remain unmarked; collectibles and valuables are intentionally hidden from scanner detection. |
| Procedural challenge | Obstacles and routes are generated with playability validation. |
| Roguelite progression | Temporary upgrades during a run and persistent unlocks between runs. |

## 🧭 Initial gameplay loop

1. Start a descent with selected equipment.
2. Move downward automatically.
3. Read threat signals and choose a lateral route.
4. Avoid hazards and discover resources through observation.
5. Acquire temporary upgrades and enter new underground strata.
6. End the run, retain eligible progression and prepare another descent.

## 🛠️ Technology

| Tool | Intended use |
|---|---|
| Unreal Engine 5.8 | Runtime, gameplay, physics, rendering and PCG |
| C++ | Core gameplay systems |
| Blueprints | Presentation, animation, effects and tuning |
| Blender | Modeling, UVs, materials and optimization |
| Tripo | AI-assisted 3D asset generation |
| OpenCode | AI-assisted implementation |
| Git + Git LFS | Version control and large binary assets |
| Craft Anything | Reference-game study, where suitable |

## 🧪 First playable prototype

- [ ] Automatic downward movement
- [ ] Lateral movement between logical columns
- [ ] Threat-only scanner
- [ ] Three initial hazard types
- [ ] One collectible/resource type (not revealed by scanner)
- [ ] Seeded procedural challenge generation
- [ ] Route validation
- [ ] Collision, run failure and restart

**Prototype with graybox geometry first.** No final character, elaborate environment or large asset production is required for this milestone.

## 👥 Team workflow

GitHub is the source of truth for approved work.

- **Issues:** tasks, bugs and proposals.
- **Pull Requests:** code and documentation changes for review.
- **Discussions:** open design questions.
- **Projects:** team task board.
- **`docs/decisions/`:** approved decisions and rationale.
- **`docs/contributions/`:** reports from team members and AI agents.

AI-generated output is a proposal until reviewed and approved by a human team member. Record what changed, why, affected files, tests and unresolved questions.

## 📚 Documentation

- [Game Design Document](docs/GDD.md)
- [Gameplay mechanics](docs/MECHANICS.md)
- [Architecture](docs/ARCHITECTURE.md)
- [Decision log](docs/DECISIONS.md)
- [Team workflow](docs/CONTRIBUTING.md)
- [AI agent instructions](AGENTS.md)

## 🚧 Current status

**Pre-production — concept and team workflow setup.** The project is preparing its first Unreal Engine prototype.

<div align="center">**DESCENT** · *The deeper you go, the less you can trust what you see.*</div>
