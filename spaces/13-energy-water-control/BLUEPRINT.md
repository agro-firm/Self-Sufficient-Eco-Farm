# Energy & Clean-Water Control — Blueprint Authority

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

- **Space:** Energy & Clean-Water Control
- **Parent area:** 800 m² / 8,611 ft²
- **Geometry:** south service utility rectangle
- **L1:** X 84.467–99.549 m; Y 12.828–65.871 m
- **Status:** PROVISIONAL L1 unless a later approved drawing supersedes it

## Actual blueprint functional schedule

| ID | Blueprint section | Area | Function |
|---|---|---:|---|
| B01 | Battery / inverter room | 150 m² / 1,615 ft² | electrical storage/conversion |
| B02 | Water treatment | 150 m² / 1,615 ft² | clean-water processing |
| B03 | Pump / control area | 100 m² / 1,076 ft² | water and utility control |
| B04 | Raw + treated water tanks | 120 m² / 1,292 ft² | buffer storage |
| B05 | MDB / communications / monitoring | 80 m² / 861 ft² | distribution and controls |
| B06 | Service / fire / maintenance buffer | 200 m² / 2,153 ft² | clearances and safe access |
|  | **Total** | **800 m² / 8,611 ft²** |  |

## Four-side context — show only small neighbor strips

A one-space blueprint must draw **this target space in full**. For orientation, show only a **small contextual strip (typically 5–15% of sheet depth)** beyond each visible boundary. Do **not** fully draw the neighboring spaces unless requested.

| Side | Small contextual neighbor to show |
|---|---|
| North | fodder bank (not the vegetable zone) |
| South | perimeter fire/service road |
| East | quarantine/emergency reserve |
| West | processing/storage hub |

Neighbor strips should be lighter/greyed/hatched and labeled **CONTEXT ONLY — NOT PART OF THIS SPACE**.

## Required blueprint layers / elements

- battery/inverter room
- main switchgear
- water treatment
- pump/control
- raw/treated tanks
- critical/noncritical distribution
- solar/generator interfaces
- sampling points
- communications/NVR interfaces
- fire/service clearances

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
                 [ fodder bank (not the vegetable zone) ]
        ┌─────────────────────────────────┐
 WEST   │                                 │   EAST
[processing/storage hub]  │      Energy & Clean-Water Control      │ [quarantine/emergency reserve]
        │                                 │
        └─────────────────────────────────┘
                 [ perimeter fire/service road ]
                              SOUTH
```

## Blueprint image prompt

> Create a precise technical blueprint of **Energy & Clean-Water Control**. Read this BLUEPRINT.md, ARCHITECTURE.md, SPACE.md, all system files, the L1 Coordinate Master Plan, and the `eco-farm-space-blueprint` skill first. Draw the target space in full at 800 m² (8,611 ft²), using X 84.467–99.549 m; Y 12.828–65.871 m. Show and label these internal sections: Battery / inverter room 150 m²; Water treatment 150 m²; Pump / control area 100 m²; Raw + treated water tanks 120 m²; MDB / communications / monitoring 80 m²; Service / fire / maintenance buffer 200 m². Include north arrow, scale/status, legend, access, drainage/water, electrical/lighting, CCTV/security/safety layers as applicable. Show only small grey/context strips on the four sides: north = fodder bank (not the vegetable zone); south = perimeter fire/service road; east = quarantine/emergency reserve; west = processing/storage hub. Do not fully draw neighboring spaces. Mark every unapproved internal dimension **PROVISIONAL**.

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
