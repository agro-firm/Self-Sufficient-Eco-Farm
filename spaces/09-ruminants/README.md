# Cattle, Goat & Sheep District

This folder is the detailed documentation authority for the **Cattle, Goat & Sheep District** space.

## At a glance

| Item | Value |
|---|---|
| Farm area allocation | **3,200 m² / 34,445 ft²** |
| L1 geometry | South-east-central service rectangle. |
| L1 coordinate authority | X 146.680–207.008 m; Y 12.828–65.871 m. L1 block ≈60.328 × 53.043 m. |
| Status | **PROVISIONAL L1** — authoritative for repository drawings/images, not legal/construction staking |

## Purpose

- cattle housing
- goat/sheep housing
- yards
- maternity/youngstock
- feeding/milking
- manure collection

## Required skills

- [`eco-farm-ruminant-space`](../../.agents/skills/eco-farm-ruminant-space/SKILL.md)
- [`eco-farm-ruminant-livestock`](../../.agents/skills/eco-farm-ruminant-livestock/SKILL.md)
- [`eco-farm-fodder-feed`](../../.agents/skills/eco-farm-fodder-feed/SKILL.md)
- [`eco-farm-biosecurity-animal-health`](../../.agents/skills/eco-farm-biosecurity-animal-health/SKILL.md)

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
    A["Fodder north"]
    S["Cattle, Goat & Sheep District"]
    B["Biogas east"]
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
