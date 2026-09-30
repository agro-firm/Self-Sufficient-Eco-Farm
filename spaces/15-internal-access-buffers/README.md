# Internal Access Spines, Biosecurity Buffers, Headlands & Swales

This folder is the detailed documentation authority for the **Internal Access Spines, Biosecurity Buffers, Headlands & Swales** space.

## At a glance

| Item | Value |
|---|---|
| Farm area allocation | **3,000 m² / 32,292 ft²** |
| L1 geometry | Three west-side distributed strips plus internal support functions. |
| L1 coordinate authority | South strip X 12.828–31.680, Y 12.828–65.871; Middle strip X 12.828–25.648, Y 65.871–143.877; North strip X 12.828–28.627, Y 143.877–207.172. West clean spine concept X 16–21 m across internal core. |
| Status | **PROVISIONAL L1** — authoritative for repository drawings/images, not legal/construction staking |

## Purpose

- internal access
- biosecurity separation
- headlands/turning
- vegetated swales
- fire breaks
- utility corridors

## Required skills

- [`eco-farm-master-planning`](../../.agents/skills/eco-farm-master-planning/SKILL.md)
- [`eco-farm-land-civil-zoning`](../../.agents/skills/eco-farm-land-civil-zoning/SKILL.md)
- [`eco-farm-roads-gates-traffic-space`](../../.agents/skills/eco-farm-roads-gates-traffic-space/SKILL.md)
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
    A["Touches all three internal horizontal bands"]
    S["Internal Access Spines, Biosecurity Buffers, Headlands & Swales"]
    B["Connects to main clean gate"]
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
