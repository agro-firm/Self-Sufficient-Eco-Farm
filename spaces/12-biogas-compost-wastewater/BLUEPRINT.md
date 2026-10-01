# Biogas, Compost & Wastewater Treatment — Blueprint Authority

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

- **Space:** Biogas, Compost & Wastewater Treatment
- **Parent area:** 1,600 m² / 17,222 ft²
- **Geometry:** far south-east treatment rectangle
- **L1:** X 207.008–237.172 m; Y 12.828–65.871 m
- **Status:** PROVISIONAL L1 unless a later approved drawing supersedes it

## Actual blueprint functional schedule

| ID | Blueprint section | Area | Function |
|---|---|---:|---|
| B01 | Digester / main equipment | 300 m² / 3,229 ft² | anaerobic digestion |
| B02 | Solids separation / equalization | 200 m² / 2,153 ft² | feedstock pretreatment |
| B03 | Compost / digestate maturation | 450 m² / 4,844 ft² | solid nutrient recovery |
| B04 | Wastewater treatment | 300 m² / 3,229 ft² | liquid treatment |
| B05 | Gas handling / generator interface | 100 m² / 1,076 ft² | gas storage/control interface |
| B06 | Service / safety buffer | 250 m² / 2,691 ft² | access, separation and containment |
|  | **Total** | **1,600 m² / 17,222 ft²** |  |

## Four-side context — show only small neighbor strips

A one-space blueprint must draw **this target space in full**. For orientation, show only a **small contextual strip (typically 5–15% of sheet depth)** beyond each visible boundary. Do **not** fully draw the neighboring spaces unless requested.

| Side | Small contextual neighbor to show |
|---|---|
| North | fodder bank |
| South | perimeter fire/service road |
| East | perimeter fire/service road |
| West | ruminant district |

Neighbor strips should be lighter/greyed/hatched and labeled **CONTEXT ONLY — NOT PART OF THIS SPACE**.

## Required blueprint layers / elements

- manure receiving
- solid separation/equalization
- digester
- gas storage/piping
- generator interface
- digestate treatment
- compost bays
- wastewater treatment cells
- sludge route
- sampling points
- reuse/outfall
- hazard separation

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
[ruminant district]  │      Biogas, Compost & Wastewater Treatment      │ [perimeter fire/service road]
        │                                 │
        └─────────────────────────────────┘
                 [ perimeter fire/service road ]
                              SOUTH
```

## Blueprint image prompt

> Create a precise technical blueprint of **Biogas, Compost & Wastewater Treatment**. Read this BLUEPRINT.md, ARCHITECTURE.md, SPACE.md, all system files, the L1 Coordinate Master Plan, and the `eco-farm-space-blueprint` skill first. Draw the target space in full at 1,600 m² (17,222 ft²), using X 207.008–237.172 m; Y 12.828–65.871 m. Show and label these internal sections: Digester / main equipment 300 m²; Solids separation / equalization 200 m²; Compost / digestate maturation 450 m²; Wastewater treatment 300 m²; Gas handling / generator interface 100 m²; Service / safety buffer 250 m². Include north arrow, scale/status, legend, access, drainage/water, electrical/lighting, CCTV/security/safety layers as applicable. Show only small grey/context strips on the four sides: north = fodder bank; south = perimeter fire/service road; east = perimeter fire/service road; west = ruminant district. Do not fully draw neighboring spaces. Mark every unapproved internal dimension **PROVISIONAL**.

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
