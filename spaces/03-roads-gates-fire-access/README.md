# Perimeter Roads, Gates & Fire Access

This folder is the detailed documentation authority for the **Perimeter Roads, Gates & Fire Access** space.

## At a glance

| Item | Value |
|---|---|
| Farm area allocation | **4,200 m² / 45,208 ft²** |
| L1 geometry | Continuous perimeter fire/service road ring plus gate/bridge approaches and edge drains. |
| L1 coordinate authority | Road ring lies between canal inner control at inset 7.927 m and internal-core control at inset 12.828 m; average width ≈ 4.901 m. Main gate X 15–21 m south edge; service gate X 222–227 m south edge. |
| Status | **PROVISIONAL L1** — authoritative for repository drawings/images, not legal/construction staking |

## Purpose

- fire access
- service circulation
- gate approaches
- maintenance
- edge drainage

## Required skills

- [`eco-farm-roads-gates-traffic-space`](../../.agents/skills/eco-farm-roads-gates-traffic-space/SKILL.md)
- [`eco-farm-land-civil-zoning`](../../.agents/skills/eco-farm-land-civil-zoning/SKILL.md)
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
    A["Canal outside"]
    S["Perimeter Roads, Gates & Fire Access"]
    B["Internal farm core inside"]
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
