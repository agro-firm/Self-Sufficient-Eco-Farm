# House, Admin, Playground, Garage & Swimming Pool — Blueprint Authority

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

- **Space:** House, Admin, Playground, Garage & Swimming Pool
- **Parent area:** 2,200 m² / 23,681 ft²
- **Geometry:** north-west clean rectangular residential/admin block
- **L1:** X 28.627–63.384 m; Y 143.877–207.172 m
- **Status:** PROVISIONAL L1 unless a later approved drawing supersedes it

## Actual blueprint functional schedule

| ID | Blueprint section | Area | Function |
|---|---|---:|---|
| B01 | 2-story house/admin footprint | 480 m² / 5,167 ft² | two-floor residence + admin/control |
| B02 | Playground | 600 m² / 6,458 ft² | 20×30 m play/emergency assembly |
| B03 | Residential/admin garage | 120 m² / 1,292 ft² | light vehicles / optional EV |
| B04 | Swimming-pool water | 60 m² / 646 ft² | concept ~12×5 m family pool |
| B05 | Pool deck / safety / equipment | 140 m² / 1,507 ft² | barrier, deck, pool plant |
| B06 | Arrival drive / drop-off / pedestrian courts | 260 m² / 2,799 ft² | clean access and movement |
| B07 | Utility / service area | 120 m² / 1,292 ft² | meters, pool/service support |
| B08 | Drainage / pervious / safety buffers | 420 m² / 4,521 ft² | rain-garden, pervious and setbacks |
|  | **Total** | **2,200 m² / 23,681 ft²** |  |

## Four-side context — show only small neighbor strips

A one-space blueprint must draw **this target space in full**. For orientation, show only a **small contextual strip (typically 5–15% of sheet depth)** beyond each visible boundary. Do **not** fully draw the neighboring spaces unless requested.

| Side | Small contextual neighbor to show |
|---|---|
| North | perimeter fire/service road beyond the north block edge |
| South | clean internal circulation toward vegetable/production areas |
| East | human-food crop block |
| West | clean internal access/buffer strip |

Neighbor strips should be lighter/greyed/hatched and labeled **CONTEXT ONLY — NOT PART OF THIS SPACE**.

## Required blueprint layers / elements

- site plan
- ground-floor plan
- first-floor plan
- roof/solar plan
- four elevations
- sections
- garage/parking
- pool/barrier/plant
- playground
- drainage
- water/plumbing
- electrical
- lighting
- CCTV/data/access
- fire/life safety

## Minimum drawing set

1. **BP-01 — Architectural / functional top plan:** all internal sections, labels, areas, access, north arrow and four side context.
2. **BP-02 — Dimensions & space-management plan:** parent dimensions/coordinates, internal provisional dimensions, setbacks/clearances.
3. **BP-03 — Drainage/water plan:** drains, swales, tanks/intakes/outfalls/treatment interface as applicable.
4. **BP-04 — Electrical/lighting plan:** power routes, critical loads, lights, isolation points as applicable.
5. **BP-05 — CCTV/security/safety plan:** cameras/access/biosecurity/fire/emergency features as applicable.
6. **BP-06 — Sections/elevations/details:** at least the sections needed to explain heights, slopes, banks, roofs, sheds, tanks, rows or yards.
7. **BP-07 — Building set:** ground floor, first floor, roof/solar, four elevations, building sections, garage, pool and playground.


## Simple blueprint diagram — not to scale

```text
                              NORTH
                 [ perimeter fire/service road beyond the north block edge ]
        ┌─────────────────────────────────┐
 WEST   │                                 │   EAST
[clean internal access/buffer strip]  │      House, Admin, Playground, Garage & Swimming Pool      │ [human-food crop block]
        │                                 │
        └─────────────────────────────────┘
                 [ clean internal circulation toward vegetable/production areas ]
                              SOUTH
```

## Blueprint image prompt

> Create a precise technical blueprint of **House, Admin, Playground, Garage & Swimming Pool**. Read this BLUEPRINT.md, ARCHITECTURE.md, SPACE.md, all system files, the L1 Coordinate Master Plan, and the `eco-farm-space-blueprint` skill first. Draw the target space in full at 2,200 m² (23,681 ft²), using X 28.627–63.384 m; Y 143.877–207.172 m. Show and label these internal sections: 2-story house/admin footprint 480 m²; Playground 600 m²; Residential/admin garage 120 m²; Swimming-pool water 60 m²; Pool deck / safety / equipment 140 m²; Arrival drive / drop-off / pedestrian courts 260 m²; Utility / service area 120 m²; Drainage / pervious / safety buffers 420 m². Include north arrow, scale/status, legend, access, drainage/water, electrical/lighting, CCTV/security/safety layers as applicable. Show only small grey/context strips on the four sides: north = perimeter fire/service road beyond the north block edge; south = clean internal circulation toward vegetable/production areas; east = human-food crop block; west = clean internal access/buffer strip. Do not fully draw neighboring spaces. Mark every unapproved internal dimension **PROVISIONAL**.

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
