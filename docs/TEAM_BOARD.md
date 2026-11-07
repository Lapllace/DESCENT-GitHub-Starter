# DESCENT — Team board setup

## Create the board
1. Open the repository and select **Projects**.
2. Choose **New project** → **Board**.
3. Name: **DESCENT — Development Roadmap**.
4. Description: *Planning, research and production tracking for DESCENT.*
5. Keep visibility aligned with the repository and add this repository as a source.

If the repository Projects tab is unavailable, create the project from your GitHub profile's Projects page and add this repository as a source.

## Status columns
| Status | Meaning |
|---|---|
| Backlog | Valid task, not prioritized |
| Ready | Scope is clear and ready to start |
| In progress | One person is actively responsible |
| In review | Waiting for team or technical review |
| Blocked | Cannot proceed; blocker is documented |
| Done | Acceptance criteria met and reviewed |

## Recommended fields
- **Priority:** P0 / P1 / P2 / P3
- **Area:** Research / Game Design / Gameplay / Scanner / Procedural Generation / Art / Audio / Tools
- **Iteration:** milestone or sprint
- **Assignee:** one accountable owner
- **Status:** values above

## Suggested views
- **Team board:** Kanban grouped by Status.
- **Research & design:** filter Area to Research and Game Design.
- **Prototype:** filter Area to Gameplay, Scanner and Procedural Generation.
- **My work:** filter by Assignee.

## First milestone
**M0 — Foundation & Graybox Plan**
1. Comparative research and originality review.
2. Resolve graybox movement and camera parameters.
3. Specify threat-only scanner behavior.
4. Define initial hazards, collectible and route validation rules.
5. Implement graybox movement after design parameters are reviewed.

## Team rules
- Every task needs an Issue, one owner and acceptance criteria.
- Keep proposals separate from approved decisions.
- Link pull requests to Issues.
- Record AI tool/model and summarize AI contributions.
- Review evidence before marking work Done.
- Do not edit the same Unreal `.uasset` or `.umap` concurrently; coordinate ownership and Git LFS locking.

## First meeting checklist
- [ ] Invite collaborators.
- [ ] Confirm repository visibility and access.
- [ ] Create the board and add this repository.
- [ ] Assign one accountable owner per Issue.
- [ ] Agree where contribution reports will be recorded.
