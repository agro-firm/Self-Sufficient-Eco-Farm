# Energy & Clean-Water Control

This folder is the detailed documentation authority for the **Energy & Clean-Water Control** space.

## At a glance

| Item | Value |
|---|---|
| Farm area allocation | **800 m² / 8,611 ft²** |
| L1 geometry | South service rectangle between processing and quarantine. |
| L1 coordinate authority | X 84.467–99.549 m; Y 12.828–65.871 m. L1 block ≈15.082 × 53.043 m. |
| Status | **PROVISIONAL L1** — authoritative for repository drawings/images, not legal/construction staking |

## Purpose

- battery/inverter
- main electrical distribution
- water treatment
- pump controls
- monitoring
- critical utilities

## Required skills

- [`eco-farm-energy-water-control-space`](../../.agents/skills/eco-farm-energy-water-control-space/SKILL.md)
- [`eco-farm-energy-electrical`](../../.agents/skills/eco-farm-energy-electrical/SKILL.md)
- [`eco-farm-electrical-lighting-cctv`](../../.agents/skills/eco-farm-electrical-lighting-cctv/SKILL.md)
- [`eco-farm-water-treatment-space`](../../.agents/skills/eco-farm-water-treatment-space/SKILL.md)

## Folder documents

- [Architecture](ARCHITECTURE.md) — physical organization, adjacency and internal architecture
- [Space](SPACE.md) — area, coordinates, dimensions and subspace budget
- [Design](DESIGN.md) — design rules, safety, environmental and material concepts
- [Image](IMAGE.md) — blueprint/render/image-generation rules
- [Details](DETAILS.md) — complete component/interface description
- [Utilities](UTILITIES.md) — power, water, drainage, data, fire and waste interfaces
- [Operations](OPERATIONS.md) — operating routines, records and KPIs
- [WATER TREATMENT](WATER_TREATMENT.md) — dedicated subspace detail
- [ELECTRICAL CCTV](ELECTRICAL_CCTV.md) — dedicated subspace detail

## Neighbor relationship

```mermaid
flowchart LR
    A["Processing west"]
    S["Energy & Clean-Water Control"]
    B["Quarantine east"]
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
