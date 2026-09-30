# Security Wall, Inspection & Privacy Band

This folder is the detailed documentation authority for the **Security Wall, Inspection & Privacy Band** space.

## At a glance

| Item | Value |
|---|---|
| Farm area allocation | **1,800 m² / 19,375 ft²** |
| L1 geometry | Continuous outer security ring. |
| L1 coordinate authority | Plot edge to inner control at 1.931 m average gross inset. Local service/CCTV bays may widen. |
| Status | **PROVISIONAL L1** — authoritative for repository drawings/images, not legal/construction staking |

## Purpose

- physical security
- privacy
- inspection/patrol
- CCTV/light support
- boundary maintenance

## Required skills

- [`eco-farm-perimeter-wall-security-space`](../../.agents/skills/eco-farm-perimeter-wall-security-space/SKILL.md)
- [`eco-farm-security-resilience`](../../.agents/skills/eco-farm-security-resilience/SKILL.md)
- [`eco-farm-electrical-lighting-cctv`](../../.agents/skills/eco-farm-electrical-lighting-cctv/SKILL.md)

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
    A["Legal/planning boundary outside"]
    S["Security Wall, Inspection & Privacy Band"]
    B["Perimeter canal inside"]
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
