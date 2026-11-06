# Gameplay mechanics — initial specification

## Descent
Automatic continuous downward movement. Speed progression must not make hazards mathematically unavoidable.

## Lateral traversal
Shift between adjacent logical columns while downward motion continues. Communicate the transition through animation/VFX. Prototype a finite set of columns before exploring unbounded lateral coordinates.

## Threat-only scanner
| Target | Scanner result |
|---|---|
| Relevant hazard | Mark / warning |
| Safe open space | No mark |
| Collectible | No mark |
| Valuable resource | No mark |
| Ordinary environmental object | No mark |

Scanner output must be timely enough for human reaction. Do not expose hidden loot through outlines, pings or indirect UI. Upgrades may change range or clarity while preserving threat-only identity unless a documented design change is approved.

## Procedural generation
Keep gameplay layout generation (columns, hazards, gaps, resources, route constraints) separate from decorative environment generation (rocks, debris, crystals, background structures, particles). Use deterministic seeds for reproducible tests. Validate at least one traversable route through every generated challenge segment.

## Failure and roguelite systems
The prototype needs reliable collision, clear feedback and restart. Keep temporary run upgrades separate from persistent meta-progression.
