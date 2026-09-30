# Human Food Crop Zone

This folder is the detailed documentation authority for the **Human Food Crop Zone** space.

## At a glance

| Item | Value |
|---|---|
| Farm area allocation | **6,500 m² / 69,965 ft²** |
| L1 geometry | North-central open-sun rectangle. |
| L1 coordinate authority | X 63.384–166.077 m; Y 143.877–207.172 m. L1 block ≈102.693 × 63.296 m. |
| Status | **PROVISIONAL L1** — authoritative for repository drawings/images, not legal/construction staking |

## Purpose

- rice
- maize
- pulses/legumes
- mustard/sesame
- human food and feed by-products

## Required skills

- [`eco-farm-food-crop-space`](../../.agents/skills/eco-farm-food-crop-space/SKILL.md)
- [`eco-farm-crops-horticulture`](../../.agents/skills/eco-farm-crops-horticulture/SKILL.md)
- [`eco-farm-water-drainage-wastewater`](../../.agents/skills/eco-farm-water-drainage-wastewater/SKILL.md)

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
    A["House/admin west"]
    S["Human Food Crop Zone"]
    B["Orchard east"]
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
