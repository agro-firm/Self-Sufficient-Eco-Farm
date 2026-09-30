# Perimeter Canal

This folder is the detailed documentation authority for the **Perimeter Canal** space.

## At a glance

| Item | Value |
|---|---|
| Farm area allocation | **5,400 m² / 58,125 ft²** |
| L1 geometry | Continuous ring between the security/inspection band and the perimeter fire/service road. |
| L1 coordinate authority | Outer control: inset 1.931 m. Inner canal control: inset 7.927 m. Derived planning water width ≈ 5.996 m. |
| Status | **PROVISIONAL L1** — authoritative for repository drawings/images, not legal/construction staking |

## Purpose

- fish production
- flood/stormwater retention
- irrigation reserve
- fire-water reserve
- security separation

## Required skills

- [`eco-farm-perimeter-canal-space`](../../.agents/skills/eco-farm-perimeter-canal-space/SKILL.md)
- [`eco-farm-canal-aquaculture`](../../.agents/skills/eco-farm-canal-aquaculture/SKILL.md)
- [`eco-farm-water-drainage-wastewater`](../../.agents/skills/eco-farm-water-drainage-wastewater/SKILL.md)
- [`eco-farm-security-resilience`](../../.agents/skills/eco-farm-security-resilience/SKILL.md)

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
    A["Security wall/inspection band outside"]
    S["Perimeter Canal"]
    B["Perimeter fire/service road inside"]
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
