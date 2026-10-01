# Security Wall, Inspection & Privacy Band — Blueprint Authority

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

- **Space:** Security Wall, Inspection & Privacy Band
- **Parent area:** 1,800 m² / 19,375 ft²
- **Geometry:** continuous outer perimeter security band, equivalent average gross width about 1.931 m with local wider bays
- **L1:** legal/planning boundary to inner security control line at ~1.931 m inset
- **Status:** PROVISIONAL L1 unless a later approved drawing supersedes it

## Generated blueprint reference

![Security perimeter — PROVISIONAL L1 blueprint master](images/01-blueprint-master.png)

> Visual reference only; written schedules and L1 registry control discrepancies.

## Actual blueprint functional schedule

| ID | Blueprint section | Area | Function |
|---|---|---:|---|
| B01 | Wall / footing reservation | 400 m² / 4,306 ft² | hard perimeter security line |
| B02 | Inspection / patrol clear band | 650 m² / 6,997 ft² | maintenance and patrol |
| B03 | Gate / security service bays | 250 m² / 2,691 ft² | gate piers, control and access |
| B04 | Low/medium privacy planting | 300 m² / 3,229 ft² | privacy without major crop shading |
| B05 | CCTV / lighting service pockets | 100 m² / 1,076 ft² | security equipment clearances |
| B06 | Drainage / utility edge | 100 m² / 1,076 ft² | wall-footing drainage and services |
|  | **Total** | **1,800 m² / 19,375 ft²** |  |

## Four-side context — show only small neighbor strips

A one-space blueprint must draw **this target space in full**. For orientation, show only a **small contextual strip (typically 5–15% of sheet depth)** beyond each visible boundary. Do **not** fully draw the neighboring spaces unless requested.

| Side | Small contextual neighbor to show |
|---|---|
| North | outside property beyond wall; canal immediately inside |
| South | outside property beyond wall; main clean gate and service/emergency gate occur on south edge; canal inside |
| East | outside property beyond wall; canal immediately inside |
| West | outside property beyond wall; canal immediately inside |

Neighbor strips should be lighter/greyed/hatched and labeled **CONTEXT ONLY — NOT PART OF THIS SPACE**.

## Required blueprint layers / elements

- legal boundary/wall line
- gate openings/piers
- inspection strip/bays
- privacy planting zones
- CCTV/light points
- drainage
- canal setback interface

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
                 [ outside property beyond wall; canal immediately inside ]
        ┌─────────────────────────────────┐
 WEST   │                                 │   EAST
[outside property beyond wall; canal immediately inside]  │      Security Wall, Inspection & Privacy Band      │ [outside property beyond wall; canal immediately inside]
        │                                 │
        └─────────────────────────────────┘
                 [ outside property beyond wall; main clean gate and service/emergency gate occur on south edge; canal inside ]
                              SOUTH
```

## Blueprint image prompt

> Create a precise technical blueprint of **Security Wall, Inspection & Privacy Band**. Read this BLUEPRINT.md, ARCHITECTURE.md, SPACE.md, all system files, the L1 Coordinate Master Plan, and the `eco-farm-space-blueprint` skill first. Draw the target space in full at 1,800 m² (19,375 ft²), using legal/planning boundary to inner security control line at ~1.931 m inset. Show and label these internal sections: Wall / footing reservation 400 m²; Inspection / patrol clear band 650 m²; Gate / security service bays 250 m²; Low/medium privacy planting 300 m²; CCTV / lighting service pockets 100 m²; Drainage / utility edge 100 m². Include north arrow, scale/status, legend, access, drainage/water, electrical/lighting, CCTV/security/safety layers as applicable. Show only small grey/context strips on the four sides: north = outside property beyond wall; canal immediately inside; south = outside property beyond wall; main clean gate and service/emergency gate occur on south edge; canal inside; east = outside property beyond wall; canal immediately inside; west = outside property beyond wall; canal immediately inside. Do not fully draw neighboring spaces. Mark every unapproved internal dimension **PROVISIONAL**.

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
