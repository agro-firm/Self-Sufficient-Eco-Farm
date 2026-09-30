# Vegetables, Greenhouse & Nursery

This folder is the detailed documentation authority for the **Vegetables, Greenhouse & Nursery** space.

## At a glance

| Item | Value |
|---|---|
| Farm area allocation | **4,500 m² / 48,438 ft²** |
| L1 geometry | Middle-west clean-production rectangle. |
| L1 coordinate authority | X 25.648–83.336 m; Y 65.871–143.877 m. L1 block ≈57.689 × 78.005 m. |
| Status | **PROVISIONAL L1** — authoritative for repository drawings/images, not legal/construction staking |

## Purpose

- open vegetable beds
- greenhouse/protected crops
- nursery/mother plants
- clean wash/service point

## Required skills

- [`eco-farm-vegetable-greenhouse-nursery-space`](../../.agents/skills/eco-farm-vegetable-greenhouse-nursery-space/SKILL.md)
- [`eco-farm-crops-horticulture`](../../.agents/skills/eco-farm-crops-horticulture/SKILL.md)
- [`eco-farm-water-treatment-space`](../../.agents/skills/eco-farm-water-treatment-space/SKILL.md)

## Folder documents

- [Architecture](ARCHITECTURE.md) — physical organization, adjacency and internal architecture
- [Space](SPACE.md) — area, coordinates, dimensions and subspace budget
- [Design](DESIGN.md) — design rules, safety, environmental and material concepts
- [Image](IMAGE.md) — blueprint/render/image-generation rules
- [Details](DETAILS.md) — complete component/interface description
- [Utilities](UTILITIES.md) — power, water, drainage, data, fire and waste interfaces
- [Operations](OPERATIONS.md) — operating routines, records and KPIs


## Neighbor relationship

```mermaid
flowchart LR
    A["West clean access strip"]
    S["Vegetables, Greenhouse & Nursery"]
    B["Fodder east"]
    A --- S --- B
```

## Must stay compatible with

- [`../../SPACE.md`](../../SPACE.md)
- [`../../docs/COORDINATE_MASTER_PLAN_L1.md`](../../docs/COORDINATE_MASTER_PLAN_L1.md)
- [`../../docs/SPACE_REGISTRY.md`](../../docs/SPACE_REGISTRY.md)
- [`../../docs/SPATIAL_DESIGN_STANDARD.md`](../../docs/SPATIAL_DESIGN_STANDARD.md)
- [`../../docs/IMAGE_BLUEPRINT_STANDARD.md`](../../docs/IMAGE_BLUEPRINT_STANDARD.md)
- [`../../docs/DECISIONS.md`](../../docs/DECISIONS.md)

Do not change this space's outer L1 authority without a master-plan decision and a full area/adjoining-system recheck.
