---
name: eco-farm-space-blueprint
description: Create or review a precise blueprint for any individual farm space, using its L1 placement, ARCHITECTURE.md area schedule, BLUEPRINT.md, system files, four-side neighbor context, and project precision/quality rules.
---

# Eco-Farm Space Blueprint

## Use when
Use for any request to create, revise, review, render, or prompt a blueprint/technical plan for one farm space.

## Mandatory read order
1. `docs/DECISIONS.md`
2. `docs/COORDINATE_MASTER_PLAN_L1.md`
3. `docs/SPACE_BLUEPRINT_STANDARD.md`
4. target `spaces/<space>/README.md`
5. target `ARCHITECTURE.md`
6. target `SPACE.md`
7. target `BLUEPRINT.md`
8. target system docs: `SPACE_MANAGEMENT.md`, `DRAINAGE.md`, `WATER_SYSTEM.md`, `ELECTRICAL.md`, `CCTV_SECURITY.md`, `LIGHTING.md`, `SAFETY.md`
9. relevant physical/system skills
10. `eco-farm-precision-layout-visualization`
11. finish with `eco-farm-quality-gate`

## Blueprint contract
Every individual-space blueprint must:
- draw the target space in full
- preserve parent L1 position, area and orientation
- use the exact area schedule from `ARCHITECTURE.md`
- show internal circulation, maintenance and safety space
- show only **small 5–15% context strips** for neighboring sides unless a wider context drawing is explicitly requested
- label context strips and do not count their area as part of the target
- include north arrow, legend, status and revision
- distinguish approved vs PROVISIONAL dimensions
- show the relevant system layers or provide dedicated overlay sheets
- include sections/elevations/details where top view alone cannot explain the design

## Four-side context rule
For north/south/east/west:
- use `IMAGE.md`, `ARCHITECTURE.md` and L1 coordinates to identify the true neighbor
- never guess from the previous image
- never swap/mirror a neighbor for composition
- show only enough of the neighbor to prove correct placement

## Precision
L1 coordinates can control parent-zone placement. Internal dimensions remain PROVISIONAL unless approved in a detailed drawing or registry.

## Reject if
- parent area does not reconcile
- internal areas exceed parent
- neighboring sides are wrong
- context strips are drawn as full neighboring projects without request
- system routes conflict
- unapproved dimensions are presented as construction-ready
- a photorealistic image is used as measurement authority
