# Orchard & Pollinator Zone — Blueprint Authority

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

- **Space:** Orchard & Pollinator Zone
- **Parent area:** 4,500 m² / 48,438 ft²
- **Geometry:** north-east orchard rectangle
- **L1:** X 166.077–237.172 m; Y 143.877–207.172 m
- **Status:** PROVISIONAL L1 unless a later approved drawing supersedes it

## Actual blueprint functional schedule

| ID | Blueprint section | Area | Function |
|---|---|---:|---|
| B01 | Mango | 1,500 m² / 16,146 ft² | tall-canopy fruit block |
| B02 | Guava | 750 m² / 8,073 ft² | medium-canopy fruit block |
| B03 | Citrus / lemon | 750 m² / 8,073 ft² | medium/low fruit block |
| B04 | Banana / papaya | 1,000 m² / 10,764 ft² | fast-bearing fruit layer |
| B05 | Pollinator strips / bees / paths / drains | 500 m² / 5,382 ft² | pollination, service and drainage |
|  | **Total** | **4,500 m² / 48,438 ft²** |  |

## Four-side context — show only small neighbor strips

A one-space blueprint must draw **this target space in full**. For orientation, show only a **small contextual strip (typically 5–15% of sheet depth)** beyond each visible boundary. Do **not** fully draw the neighboring spaces unless requested.

| Side | Small contextual neighbor to show |
|---|---|
| North | perimeter fire/service road |
| South | fodder bank |
| East | perimeter fire/service road |
| West | human-food crop zone |

Neighbor strips should be lighter/greyed/hatched and labeled **CONTEXT ONLY — NOT PART OF THIS SPACE**.

## Required blueprint layers / elements

- species blocks/tree grid
- mature-canopy circles/exclusion lines
- service paths
- irrigation
- drains
- pollinator strips
- beehive zone
- storm-risk setbacks

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
                 [ perimeter fire/service road ]
        ┌─────────────────────────────────┐
 WEST   │                                 │   EAST
[human-food crop zone]  │      Orchard & Pollinator Zone      │ [perimeter fire/service road]
        │                                 │
        └─────────────────────────────────┘
                 [ fodder bank ]
                              SOUTH
```

## Blueprint image prompt

> Create a precise technical blueprint of **Orchard & Pollinator Zone**. Read this BLUEPRINT.md, ARCHITECTURE.md, SPACE.md, all system files, the L1 Coordinate Master Plan, and the `eco-farm-space-blueprint` skill first. Draw the target space in full at 4,500 m² (48,438 ft²), using X 166.077–237.172 m; Y 143.877–207.172 m. Show and label these internal sections: Mango 1500 m²; Guava 750 m²; Citrus / lemon 750 m²; Banana / papaya 1000 m²; Pollinator strips / bees / paths / drains 500 m². Include north arrow, scale/status, legend, access, drainage/water, electrical/lighting, CCTV/security/safety layers as applicable. Show only small grey/context strips on the four sides: north = perimeter fire/service road; south = fodder bank; east = perimeter fire/service road; west = human-food crop zone. Do not fully draw neighboring spaces. Mark every unapproved internal dimension **PROVISIONAL**.

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
