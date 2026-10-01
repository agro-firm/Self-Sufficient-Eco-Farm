# Quarantine & Emergency Reserve — Blueprint Authority

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

- **Space:** Quarantine & Emergency Reserve
- **Parent area:** 1,000 m² / 10,764 ft²
- **Geometry:** south service isolation rectangle
- **L1:** X 99.549–118.402 m; Y 12.828–65.871 m
- **Status:** PROVISIONAL L1 unless a later approved drawing supersedes it

## Actual blueprint functional schedule

| ID | Blueprint section | Area | Function |
|---|---|---:|---|
| B01 | Controlled unloading / disinfection | 100 m² / 1,076 ft² | new/suspect animal entry |
| B02 | Isolation pens | 300 m² / 3,229 ft² | separate animal isolation |
| B03 | Exam / handling | 100 m² / 1,076 ft² | health inspection |
| B04 | Feed / water support | 50 m² / 538 ft² | dedicated supplies |
| B05 | Staff / PPE / hygiene | 50 m² / 538 ft² | biosecurity support |
| B06 | Emergency storage | 100 m² / 1,076 ft² | reserve supplies/equipment |
| B07 | Waste / drainage control | 100 m² / 1,076 ft² | separate dirty route |
| B08 | Circulation / buffer | 200 m² / 2,153 ft² | separation and access |
|  | **Total** | **1,000 m² / 10,764 ft²** |  |

## Four-side context — show only small neighbor strips

A one-space blueprint must draw **this target space in full**. For orientation, show only a **small contextual strip (typically 5–15% of sheet depth)** beyond each visible boundary. Do **not** fully draw the neighboring spaces unless requested.

| Side | Small contextual neighbor to show |
|---|---|
| North | fodder bank |
| South | perimeter fire/service road |
| East | poultry/duck district |
| West | energy & clean-water control zone |

Neighbor strips should be lighter/greyed/hatched and labeled **CONTEXT ONLY — NOT PART OF THIS SPACE**.

## Required blueprint layers / elements

- controlled entry/unloading
- disinfection
- isolation pens
- exam/handling
- dedicated feed/water
- waste/drain route
- staff/PPE point
- emergency storage
- separation fences

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
[energy & clean-water control zone]  │      Quarantine & Emergency Reserve      │ [poultry/duck district]
        │                                 │
        └─────────────────────────────────┘
                 [ perimeter fire/service road ]
                              SOUTH
```

## Blueprint image prompt

> Create a precise technical blueprint of **Quarantine & Emergency Reserve**. Read this BLUEPRINT.md, ARCHITECTURE.md, SPACE.md, all system files, the L1 Coordinate Master Plan, and the `eco-farm-space-blueprint` skill first. Draw the target space in full at 1,000 m² (10,764 ft²), using X 99.549–118.402 m; Y 12.828–65.871 m. Show and label these internal sections: Controlled unloading / disinfection 100 m²; Isolation pens 300 m²; Exam / handling 100 m²; Feed / water support 50 m²; Staff / PPE / hygiene 50 m²; Emergency storage 100 m²; Waste / drainage control 100 m²; Circulation / buffer 200 m². Include north arrow, scale/status, legend, access, drainage/water, electrical/lighting, CCTV/security/safety layers as applicable. Show only small grey/context strips on the four sides: north = fodder bank; south = perimeter fire/service road; east = poultry/duck district; west = energy & clean-water control zone. Do not fully draw neighboring spaces. Mark every unapproved internal dimension **PROVISIONAL**.

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
