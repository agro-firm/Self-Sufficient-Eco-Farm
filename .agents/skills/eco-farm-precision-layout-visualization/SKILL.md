---
name: eco-farm-precision-layout-visualization
description: Control centimeter/mm-accurate layout work, coordinate authority, blueprints, renders, and image prompts so visual outputs cannot redesign the farm.
---

# Precision Layout and Visualization

## Precision authority

Use `docs/SPATIAL_DESIGN_STANDARD.md`, `docs/SPACE_REGISTRY.md`, and `docs/COORDINATE_MASTER_PLAN_L1.md`.
- Plot basis: 250,000 mm × 220,000 mm.
- Exact centimeter/mm values are allowed only when approved in the coordinate registry or an approved engineering drawing.
- Otherwise mark dimensions/coordinates `PROVISIONAL`.
- Never derive an exact dimension from a photorealistic image.

## Workflow

1. Identify precision level L0/L1/L2/L3 from `docs/SPATIAL_DESIGN_STANDARD.md`.
2. Read authoritative zone area and adjacency.
3. For farm-wide topology and zone placement, use the accepted PROVISIONAL L1 coordinates in `docs/COORDINATE_MASTER_PLAN_L1.md` without deviation.
4. For details not yet placed inside an L1 zone (buildings, trees, equipment, drains), create a provisional sub-coordinate proposal and label every exact-looking number `PROVISIONAL`.
5. Validate zone polygons, roads, canal, buffers, and total plot closure.
6. For a blueprint, show north, scale, plot dimensions, relevant dimensions, revision, and status.
7. For photorealistic images, preserve topology and suppress text unless requested.
8. For multiple angles, one image = one angle and the farm geometry must remain identical.
9. Run `eco-farm-quality-gate` after every master image/blueprint.

## Image prompt contract

Every farm-wide image prompt must explicitly state:
- 250 m × 220 m planning plot
- continuous perimeter canal, no separate pond
- security wall outside canal system
- inner fire/service road
- house/admin/playground clean zone
- open food-crop zone with no tall shading elements
- largest internal productive block = fodder bank
- orchard separate from crop solar envelope
- livestock/poultry service-side
- compact processing/storage hub
- biogas/wastewater service-side
- rooftop solar
- two gates

## Reject conditions

Reject/regenerate if any fixed zone is missing, swapped, merged, resized beyond authority, or moved across a clean/dirty boundary without an approved decision change.
