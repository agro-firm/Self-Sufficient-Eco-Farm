# Dedicated Fodder Bank — Blueprint Authority

> Use the project blueprint skill: [`eco-farm-space-blueprint`](../../.agents/skills/eco-farm-space-blueprint/SKILL.md)

## Read before drawing

- [README](README.md)
- [Architecture](ARCHITECTURE.md)
- [Space & Coordinates](SPACE.md)
- [Space Management](SPACE_MANAGEMENT.md)
- [Design](DESIGN.md)
- [Drainage](DRAINAGE.md)
- [Water System](WATER_SYSTEM.md)
- [Electrical](ELECTRICAL.md)
- [CCTV & Security](CCTV_SECURITY.md)
- [Lighting](LIGHTING.md)
- [Safety](SAFETY.md)
- [Image Rules](IMAGE.md)
- [L1 Coordinate Master Plan](../../docs/COORDINATE_MASTER_PLAN_L1.md)
- [Space Blueprint Standard](../../docs/SPACE_BLUEPRINT_STANDARD.md)
- [Image & Blueprint Standard](../../docs/IMAGE_BLUEPRINT_STANDARD.md)

## Blueprint basis

- **Space:** Dedicated Fodder Bank
- **Parent area:** 12,000 m² / 129,167 ft²
- **Geometry:** largest middle/east production rectangle
- **L1:** X 83.336–237.172 m; Y 65.871–143.877 m
- **Status:** PROVISIONAL L1 unless a later approved drawing supersedes it

## Actual blueprint functional schedule

| ID | Blueprint section | Area | Function |
|---|---|---:|---|
| B01 | Napier / perennial fodder | 5,800 m² / 62,431 ft² | primary cut-and-carry block |
| B02 | Fodder maize / sorghum | 2,800 m² / 30,139 ft² | silage/seasonal energy fodder |
| B03 | Legume forage | 1,700 m² / 18,299 ft² | protein forage / rotation |
| B04 | Seasonal fodder / seed / controlled azolla-duckweed reserve | 1,700 m² / 18,299 ft² | seasonal flexibility and planting material |
|  | **Total** | **12,000 m² / 129,167 ft²** |  |

## Four-side context — show only small neighbor strips

A one-space blueprint must draw **this target space in full**. For orientation, show only a **small contextual strip (typically 5–15% of sheet depth)** beyond each visible boundary. Do **not** fully draw the neighboring spaces unless requested.

| Side | Small contextual neighbor to show |
|---|---|
| North | human-food crops on the northwest/north-central edge + orchard on the northeast edge |
| South | service band containing energy/water, quarantine, poultry, ruminants and biogas/treatment |
| East | perimeter fire/service road |
| West | vegetables/greenhouse/nursery zone |

Neighbor strips should be lighter/greyed/hatched and labeled **CONTEXT ONLY — NOT PART OF THIS SPACE**.

## Required blueprint layers / elements

- fodder sub-blocks
- harvest lanes
- irrigation/drainage
- silage-haul route
- seed/planting-material section
- emergency reserve block
- soil-monitoring points

## Minimum drawing set

1. **BP-01 — Architectural / functional top plan:** all internal sections, labels, areas, access, north arrow and four side context.
2. **BP-02 — Dimensions & space-management plan:** parent dimensions/coordinates, internal provisional dimensions, setbacks/clearances.
3. **BP-03 — Drainage/water plan:** drains, swales, tanks/intakes/outfalls/treatment interface as applicable.
4. **BP-04 — Electrical/lighting plan:** power routes, critical loads, lights, isolation points as applicable.
5. **BP-05 — CCTV/security/safety plan:** cameras/access/biosecurity/fire/emergency features as applicable.
6. **BP-06 — Sections/elevations/details:** at least the sections needed to explain heights, slopes, banks, roofs, sheds, tanks, rows or yards.


## Simple blueprint diagram — not to scale

```text
                              NORTH
                 [ human-food crops on the northwest/north-central edge + orchard on the northeast edge ]
        ┌─────────────────────────────────┐
 WEST   │                                 │   EAST
[vegetables/greenhouse/nursery zone]  │      Dedicated Fodder Bank      │ [perimeter fire/service road]
        │                                 │
        └─────────────────────────────────┘
                 [ service band containing energy/water, quarantine, poultry, ruminants and biogas/treatment ]
                              SOUTH
```

## Blueprint image prompt

> Create a precise technical blueprint of **Dedicated Fodder Bank**. Read this BLUEPRINT.md, ARCHITECTURE.md, SPACE.md, all system files, the L1 Coordinate Master Plan, and the `eco-farm-space-blueprint` skill first. Draw the target space in full at 12,000 m² (129,167 ft²), using X 83.336–237.172 m; Y 65.871–143.877 m. Show and label these internal sections: Napier / perennial fodder 5800 m²; Fodder maize / sorghum 2800 m²; Legume forage 1700 m²; Seasonal fodder / seed / controlled azolla-duckweed reserve 1700 m². Include north arrow, scale/status, legend, access, drainage/water, electrical/lighting, CCTV/security/safety layers as applicable. Show only small grey/context strips on the four sides: north = human-food crops on the northwest/north-central edge + orchard on the northeast edge; south = service band containing energy/water, quarantine, poultry, ruminants and biogas/treatment; east = perimeter fire/service road; west = vegetables/greenhouse/nursery zone. Do not fully draw neighboring spaces. Mark every unapproved internal dimension **PROVISIONAL**.

## Acceptance checklist

- [ ] Parent area total is exact
- [ ] Internal area schedule sums to parent
- [ ] North orientation and L1 context are correct
- [ ] Four-side context uses small strips, not full neighbor drawings
- [ ] Architecture and system files are reflected
- [ ] No invented feature or unapproved precision
- [ ] Legend, status and revision are present
- [ ] Relevant sections/details are included
- [ ] Quality gate passes
