# Cattle, Goat & Sheep District — Blueprint Authority

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

- **Space:** Cattle, Goat & Sheep District
- **Parent area:** 3,200 m² / 34,444 ft²
- **Geometry:** south-east-central livestock rectangle
- **L1:** X 146.680–207.008 m; Y 12.828–65.871 m
- **Status:** PROVISIONAL L1 unless a later approved drawing supersedes it

## Actual blueprint functional schedule

| ID | Blueprint section | Area | Function |
|---|---|---:|---|
| B01 | Cattle shed | 400 m² / 4,306 ft² | covered resting/housing |
| B02 | Cattle yard | 600 m² / 6,458 ft² | exercise and handling |
| B03 | Goat / sheep area | 350 m² / 3,767 ft² | separate small-ruminant housing/yard |
| B04 | Maternity / youngstock | 300 m² / 3,229 ft² | protected animal-care zone |
| B05 | Milking / handling | 150 m² / 1,615 ft² | clean handling where used |
| B06 | Feed alley / local feed storage | 300 m² / 3,229 ft² | clean feed-side circulation |
| B07 | Manure lanes / wash control | 250 m² / 2,691 ft² | dirty-side transfer |
| B08 | Circulation / ventilation / safety buffers | 850 m² / 9,149 ft² | internal movement and separation |
|  | **Total** | **3,200 m² / 34,444 ft²** |  |

## Four-side context — show only small neighbor strips

A one-space blueprint must draw **this target space in full**. For orientation, show only a **small contextual strip (typically 5–15% of sheet depth)** beyond each visible boundary. Do **not** fully draw the neighboring spaces unless requested.

| Side | Small contextual neighbor to show |
|---|---|
| North | fodder bank |
| South | perimeter fire/service road |
| East | biogas/compost/wastewater district |
| West | poultry/duck district |

Neighbor strips should be lighter/greyed/hatched and labeled **CONTEXT ONLY — NOT PART OF THIS SPACE**.

## Required blueprint layers / elements

- cattle shed/yard
- goat/sheep area
- maternity/youngstock
- feed alleys
- drinking points
- milking/handling
- manure lane
- wash/drain routes
- biosecurity entry

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
[poultry/duck district]  │      Cattle, Goat & Sheep District      │ [biogas/compost/wastewater district]
        │                                 │
        └─────────────────────────────────┘
                 [ perimeter fire/service road ]
                              SOUTH
```

## Blueprint image prompt

> Create a precise technical blueprint of **Cattle, Goat & Sheep District**. Read this BLUEPRINT.md, ARCHITECTURE.md, SPACE.md, all system files, the L1 Coordinate Master Plan, and the `eco-farm-space-blueprint` skill first. Draw the target space in full at 3,200 m² (34,444 ft²), using X 146.680–207.008 m; Y 12.828–65.871 m. Show and label these internal sections: Cattle shed 400 m²; Cattle yard 600 m²; Goat / sheep area 350 m²; Maternity / youngstock 300 m²; Milking / handling 150 m²; Feed alley / local feed storage 300 m²; Manure lanes / wash control 250 m²; Circulation / ventilation / safety buffers 850 m². Include north arrow, scale/status, legend, access, drainage/water, electrical/lighting, CCTV/security/safety layers as applicable. Show only small grey/context strips on the four sides: north = fodder bank; south = perimeter fire/service road; east = biogas/compost/wastewater district; west = poultry/duck district. Do not fully draw neighboring spaces. Mark every unapproved internal dimension **PROVISIONAL**.

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
