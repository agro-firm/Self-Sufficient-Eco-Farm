# Biogas, Compost & Wastewater Treatment

This folder is the detailed documentation authority for the **Biogas, Compost & Wastewater Treatment** space.

## At a glance

| Item | Value |
|---|---|
| Farm area allocation | **1,600 m² / 17,222 ft²** |
| L1 geometry | Far south-east service rectangle. |
| L1 coordinate authority | X 207.008–237.172 m; Y 12.828–65.871 m. L1 block ≈30.164 × 53.043 m. |
| Status | **PROVISIONAL L1** — authoritative for repository drawings/images, not legal/construction staking |

## Purpose

- manure receiving
- solid separation
- digester
- gas handling
- digestate
- composting
- wastewater treatment

## Required skills

- [`eco-farm-biogas-compost-space`](../../.agents/skills/eco-farm-biogas-compost-space/SKILL.md)
- [`eco-farm-biogas-compost-nutrients`](../../.agents/skills/eco-farm-biogas-compost-nutrients/SKILL.md)
- [`eco-farm-wastewater-treatment-space`](../../.agents/skills/eco-farm-wastewater-treatment-space/SKILL.md)
- [`eco-farm-water-drainage-wastewater`](../../.agents/skills/eco-farm-water-drainage-wastewater/SKILL.md)

## Folder documents

- [Architecture](ARCHITECTURE.md) — physical organization, adjacency and internal architecture
- [Space](SPACE.md) — area, coordinates, dimensions and subspace budget
- [Design](DESIGN.md) — design rules, safety, environmental and material concepts
- [Image](IMAGE.md) — blueprint/render/image-generation rules
- [Details](DETAILS.md) — complete component/interface description
- [Utilities](UTILITIES.md) — power, water, drainage, data, fire and waste interfaces
- [Operations](OPERATIONS.md) — operating routines, records and KPIs
- [WASTEWATER TREATMENT](WASTEWATER_TREATMENT.md) — dedicated subspace detail

## Neighbor relationship

```mermaid
flowchart LR
    A["Ruminants west"]
    S["Biogas, Compost & Wastewater Treatment"]
    B["Fodder north"]
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
