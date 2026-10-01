# Poultry & Duck District — Blueprint Authority

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

- **Space:** Poultry & Duck District
- **Parent area:** 1,500 m² / 16,146 ft²
- **Geometry:** south service bird-production rectangle
- **L1:** X 118.402–146.680 m; Y 12.828–65.871 m
- **Status:** PROVISIONAL L1 unless a later approved drawing supersedes it

## Actual blueprint functional schedule

| ID | Blueprint section | Area | Function |
|---|---|---:|---|
| B01 | Layer house | 180 m² / 1,938 ft² | egg-production house |
| B02 | Broiler house | 120 m² / 1,292 ft² | all-in/all-out meat-bird house |
| B03 | Duck house | 120 m² / 1,292 ft² | duck shelter |
| B04 | Duck wet/service yard | 350 m² / 3,767 ft² | controlled wet recreation/service |
| B05 | Feed + egg handling | 100 m² / 1,076 ft² | clean feed/egg support |
| B06 | Isolation | 80 m² / 861 ft² | bird isolation |
| B07 | Biosecurity entry / service | 150 m² / 1,615 ft² | controlled entry and sanitation |
| B08 | Circulation / buffers | 400 m² / 4,306 ft² | separation and work access |
|  | **Total** | **1,500 m² / 16,146 ft²** |  |

## Four-side context — show only small neighbor strips

A one-space blueprint must draw **this target space in full**. For orientation, show only a **small contextual strip (typically 5–15% of sheet depth)** beyond each visible boundary. Do **not** fully draw the neighboring spaces unless requested.

| Side | Small contextual neighbor to show |
|---|---|
| North | fodder bank |
| South | perimeter fire/service road |
| East | ruminant district |
| West | quarantine/emergency reserve |

Neighbor strips should be lighter/greyed/hatched and labeled **CONTEXT ONLY — NOT PART OF THIS SPACE**.

## Required blueprint layers / elements

- layer house
- broiler house
- duck house/wet pad
- biosecurity entry
- feed/egg handling
- isolation
- litter/waste route
- washwater drainage
- ventilation layout

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
                 [ fodder bank ]
        ┌─────────────────────────────────┐
 WEST   │                                 │   EAST
[quarantine/emergency reserve]  │      Poultry & Duck District      │ [ruminant district]
        │                                 │
        └─────────────────────────────────┘
                 [ perimeter fire/service road ]
                              SOUTH
```

## Blueprint image prompt

> Create a precise technical blueprint of **Poultry & Duck District**. Read this BLUEPRINT.md, ARCHITECTURE.md, SPACE.md, all system files, the L1 Coordinate Master Plan, and the `eco-farm-space-blueprint` skill first. Draw the target space in full at 1,500 m² (16,146 ft²), using X 118.402–146.680 m; Y 12.828–65.871 m. Show and label these internal sections: Layer house 180 m²; Broiler house 120 m²; Duck house 120 m²; Duck wet/service yard 350 m²; Feed + egg handling 100 m²; Isolation 80 m²; Biosecurity entry / service 150 m²; Circulation / buffers 400 m². Include north arrow, scale/status, legend, access, drainage/water, electrical/lighting, CCTV/security/safety layers as applicable. Show only small grey/context strips on the four sides: north = fodder bank; south = perimeter fire/service road; east = ruminant district; west = quarantine/emergency reserve. Do not fully draw neighboring spaces. Mark every unapproved internal dimension **PROVISIONAL**.

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
