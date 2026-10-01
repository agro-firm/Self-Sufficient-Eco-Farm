# Vegetables, Greenhouse & Nursery — Blueprint Authority

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

- **Space:** Vegetables, Greenhouse & Nursery
- **Parent area:** 4,500 m² / 48,438 ft²
- **Geometry:** middle-west clean horticulture rectangle
- **L1:** X 25.648–83.336 m; Y 65.871–143.877 m
- **Status:** PROVISIONAL L1 unless a later approved drawing supersedes it

## Actual blueprint functional schedule

| ID | Blueprint section | Area | Function |
|---|---|---:|---|
| B01 | Open rotation beds | 2,700 m² / 29,063 ft² | main vegetable production |
| B02 | Greenhouse / protected crop | 850 m² / 9,149 ft² | protected high-value production |
| B03 | Nursery / mother plants | 300 m² / 3,229 ft² | seedling and planting-material production |
| B04 | Clean wash / service point | 150 m² / 1,615 ft² | harvest handling |
| B05 | Paths / drains / internal service | 500 m² / 5,382 ft² | circulation, hygiene and water management |
|  | **Total** | **4,500 m² / 48,438 ft²** |  |

## Four-side context — show only small neighbor strips

A one-space blueprint must draw **this target space in full**. For orientation, show only a **small contextual strip (typically 5–15% of sheet depth)** beyond each visible boundary. Do **not** fully draw the neighboring spaces unless requested.

| Side | Small contextual neighbor to show |
|---|---|
| North | clean house/admin edge on the northwest portion + human-food crop edge on the northeast portion |
| South | access strip on the southwest edge + processing/storage hub across most of the south edge |
| East | fodder bank |
| West | internal access/buffer strip |

Neighbor strips should be lighter/greyed/hatched and labeled **CONTEXT ONLY — NOT PART OF THIS SPACE**.

## Required blueprint layers / elements

- open-bed layout
- greenhouse modules
- nursery/mother plants
- clean wash/service point
- paths
- drip/irrigation
- drains
- hygiene entry
- trellis/shade zones

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
                 [ clean house/admin edge on the northwest portion + human-food crop edge on the northeast portion ]
        ┌─────────────────────────────────┐
 WEST   │                                 │   EAST
[internal access/buffer strip]  │      Vegetables, Greenhouse & Nursery      │ [fodder bank]
        │                                 │
        └─────────────────────────────────┘
                 [ access strip on the southwest edge + processing/storage hub across most of the south edge ]
                              SOUTH
```

## Blueprint image prompt

> Create a precise technical blueprint of **Vegetables, Greenhouse & Nursery**. Read this BLUEPRINT.md, ARCHITECTURE.md, SPACE.md, all system files, the L1 Coordinate Master Plan, and the `eco-farm-space-blueprint` skill first. Draw the target space in full at 4,500 m² (48,438 ft²), using X 25.648–83.336 m; Y 65.871–143.877 m. Show and label these internal sections: Open rotation beds 2700 m²; Greenhouse / protected crop 850 m²; Nursery / mother plants 300 m²; Clean wash / service point 150 m²; Paths / drains / internal service 500 m². Include north arrow, scale/status, legend, access, drainage/water, electrical/lighting, CCTV/security/safety layers as applicable. Show only small grey/context strips on the four sides: north = clean house/admin edge on the northwest portion + human-food crop edge on the northeast portion; south = access strip on the southwest edge + processing/storage hub across most of the south edge; east = fodder bank; west = internal access/buffer strip. Do not fully draw neighboring spaces. Mark every unapproved internal dimension **PROVISIONAL**.

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
