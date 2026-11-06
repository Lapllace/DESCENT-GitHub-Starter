# DESCENT — Game Design Document

**Version:** 0.1 · **Status:** Pre-production · **Engine target:** Unreal Engine 5.8

## High concept
A 3D vertical endless runner with roguelite progression. The player continuously descends through a procedurally assembled underground environment, shifts laterally between logical columns and uses a scanner to anticipate threats.

## Player experience
Fast reactions, route selection, tension from incomplete information, environmental discovery and run-to-run experimentation through upgrades.

## Core pillars
1. Continuous downward movement.
2. Fluid lateral traversal.
3. Threat-only scanner.
4. Fair procedural challenge generation.
5. Roguelite upgrades and progression.
6. Underground atmosphere and environmental storytelling.

## Scanner identity
The scanner is a threat-awareness device, not a map or loot detector.
- Mark relevant hazards.
- Leave safe space visually unmarked.
- Do not reveal collectibles, valuables or ordinary objects.
- Balance detection range and warning time against descent speed and human reaction time.

## Movement
The character descends automatically. The player shifts laterally between adjacent logical columns while downward movement continues. The transition may use trails, distortion, afterimages or a phase-shift effect. Prototype with a small number of columns before exploring an effectively unbounded lateral system.

## Hazards and resources
Initial prototype: three hazard types, one collectible/resource type and one clear collision/failure condition. Hazard and collectible generation must be independent.

## Roguelite progression
Temporary upgrades during a run; persistent unlocks between runs. Potential upgrade categories: scanner, mobility, drilling and survival. Balance remains open.

## World
Underground strata/biomes with distinct visuals, hazards and resources. The first prototype needs only one graybox environment.

## Camera
Third-person is the current working hypothesis. Camera angle, distance, FOV and framing require playtesting.

## First playable acceptance criteria
- Continuous downward movement.
- Responsive lateral movement that does not interrupt descent.
- Scanner marks hazards, not safe areas or loot.
- Collectibles can be found through observation.
- Generated sequences have at least one valid route.
- Collision, failure and restart work.

## Open questions
Camera angle; initial column count and spacing; chained lateral shifts; scanner HUD/world-space presentation; descent/scanner scaling; run length; biome cadence; upgrade frequency; narrative premise.
