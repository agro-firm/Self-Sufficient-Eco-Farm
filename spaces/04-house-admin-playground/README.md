# House, Admin, Playground & Kitchen Garden

This folder is the detailed documentation authority for the **House, Admin, Playground & Kitchen Garden** space.

## At a glance

| Item | Value |
|---|---|
| Farm area allocation | **2,200 m² / 23,681 ft²** |
| L1 geometry | North-west clean/family rectangle. |
| L1 coordinate authority | X 28.627–63.384 m; Y 143.877–207.172 m. L1 block ≈34.758 × 63.296 m. |
| Status | **PROVISIONAL L1** — authoritative for repository drawings/images, not legal/construction staking |

## Purpose

- residence
- farm administration
- CCTV/NVR control
- first aid/emergency shelter
- play/recreation
- household kitchen garden

## Required skills

- [`eco-farm-house-admin-space`](../../.agents/skills/eco-farm-house-admin-space/SKILL.md)
- [`eco-farm-playground-space`](../../.agents/skills/eco-farm-playground-space/SKILL.md)
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
- [PLAYGROUND](PLAYGROUND.md) — dedicated subspace detail

## Neighbor relationship

```mermaid
flowchart LR
    A["West clean access/buffer strip"]
    S["House, Admin, Playground & Kitchen Garden"]
    B["Food-crop zone east"]
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
