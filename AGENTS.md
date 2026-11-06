# DESCENT — Instructions for AI agents

## Read first
Read `README.md`, `docs/GDD.md`, `docs/MECHANICS.md`, `docs/DECISIONS.md` and `docs/ARCHITECTURE.md` before making changes.

## Approved design rules
- The player descends continuously.
- Lateral traversal is a core player decision.
- The scanner detects relevant threats only.
- Safe areas are not marked.
- Collectibles, valuables and ordinary objects are not revealed by the scanner.
- Do not turn the scanner into a general-purpose loot detector.
- Procedural gameplay generation must validate at least one traversable route.
- Keep gameplay generation separate from decorative environment generation.
- Prototype with graybox assets before large-scale art production.

## Working rules
- An unapproved idea is not a project decision.
- Inspect repository state before editing.
- Do not overwrite or delete work without explicit authorization.
- Keep changes focused and explain changed files.
- Do not text-generate or modify Unreal binary assets (`.uasset`, `.umap`).
- Coordinate edits to shared binary assets; use Git LFS locking where configured.
- Never commit secrets, credentials, API tokens or personal data.
- Verify licenses for third-party assets.
- Never claim tests passed unless they were actually run.

## Contribution report
For substantial work, record:
- Contributor and AI tool/model (if used)
- Related Issue and goal
- Analysis and changes
- Files changed
- Decisions proposed (clearly marked)
- Tests and exact results
- Limitations and next step

## Pull Requests
Explain what changed, why, linked Issue, test steps/results, and any performance, compatibility, licensing or migration risks. Include screenshots/recording for visible gameplay changes.
