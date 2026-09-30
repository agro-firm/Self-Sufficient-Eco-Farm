# Dedicated Fodder Bank

This folder is the detailed documentation authority for the **Dedicated Fodder Bank** space.

## At a glance

| Item | Value |
|---|---|
| Farm area allocation | **12,000 m² / 129,167 ft²** |
| L1 geometry | Largest middle/east productive rectangle. |
| L1 coordinate authority | X 83.336–237.172 m; Y 65.871–143.877 m. L1 block ≈153.836 × 78.005 m. |
| Status | **PROVISIONAL L1** — authoritative for repository drawings/images, not legal/construction staking |

## Purpose

- Napier
- fodder maize/sorghum
- legume forage
- seasonal fodder
- silage production
- animal feed security

## Required skills

- [`eco-farm-fodder-bank-space`](../../.agents/skills/eco-farm-fodder-bank-space/SKILL.md)
- [`eco-farm-fodder-feed`](../../.agents/skills/eco-farm-fodder-feed/SKILL.md)
- [`eco-farm-ruminant-livestock`](../../.agents/skills/eco-farm-ruminant-livestock/SKILL.md)

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
    A["Vegetables west"]
    S["Dedicated Fodder Bank"]
    B["Ruminants/poultry/biogas south"]
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
