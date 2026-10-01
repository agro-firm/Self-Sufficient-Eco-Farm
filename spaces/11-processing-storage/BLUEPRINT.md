# Agro-Processing & Storage Hub — Blueprint Authority

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

- **Space:** Agro-Processing & Storage Hub
- **Parent area:** 2,800 m² / 30,139 ft²
- **Geometry:** south-west service/processing rectangle
- **L1:** X 31.680–84.467 m; Y 12.828–65.871 m
- **Status:** PROVISIONAL L1 unless a later approved drawing supersedes it

## Actual blueprint functional schedule

| ID | Blueprint section | Area | Function |
|---|---|---:|---|
| B01 | Crop receiving / weighing | 160 m² / 1,722 ft² | arrival and measurement |
| B02 | Covered drying | 220 m² / 2,368 ft² | weather-protected drying |
| B03 | Solar dryer | 60 m² / 646 ft² | specialty drying |
| B04 | Grain store | 400 m² / 4,306 ft² | 10–20 t base dry-grain concept |
| B05 | Rice mill | 200 m² / 2,153 ft² | 100–200 kg/h base concept |
| B06 | Feed mill | 270 m² / 2,906 ft² | farm feed processing |
| B07 | Oil press | 90 m² / 969 ft² | small oilseed processing |
| B08 | Seed bank | 90 m² / 969 ft² | seed reserve |
| B09 | Cold room + packhouse | 300 m² / 3,229 ft² | produce cold-chain |
| B10 | Clean milk/egg/fish handling | 170 m² / 1,830 ft² | clean animal-product handling |
| B11 | Workshop + spares | 260 m² / 2,799 ft² | maintenance/hot-work controlled zone |
| B12 | Silage/hay/feed logistics | 280 m² / 3,014 ft² | feed reserve support |
| B13 | Internal circulation / fire separation / utilities | 300 m² / 3,229 ft² | shared safe circulation |
|  | **Total** | **2,800 m² / 30,139 ft²** |  |

## Four-side context — show only small neighbor strips

A one-space blueprint must draw **this target space in full**. For orientation, show only a **small contextual strip (typically 5–15% of sheet depth)** beyond each visible boundary. Do **not** fully draw the neighboring spaces unless requested.

| Side | Small contextual neighbor to show |
|---|---|
| North | vegetable/greenhouse zone across almost the entire north edge, with a very narrow fodder edge at the far east |
| South | perimeter fire/service road |
| East | energy & clean-water control zone |
| West | internal access/buffer strip |

Neighbor strips should be lighter/greyed/hatched and labeled **CONTEXT ONLY — NOT PART OF THIS SPACE**.

## Required blueprint layers / elements

- receiving/weighing
- covered drying
- solar dryer
- grain store
- rice mill
- feed mill
- oil press
- seed bank
- cold room/packhouse
- clean milk/egg/fish handling
- workshop/spares
- silage/hay logistics
- circulation/fire separation

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
                 [ vegetable/greenhouse zone across almost the entire north edge, with a very narrow fodder edge at the far east ]
        ┌─────────────────────────────────┐
 WEST   │                                 │   EAST
[internal access/buffer strip]  │      Agro-Processing & Storage Hub      │ [energy & clean-water control zone]
        │                                 │
        └─────────────────────────────────┘
                 [ perimeter fire/service road ]
                              SOUTH
```

## Blueprint image prompt

> Create a precise technical blueprint of **Agro-Processing & Storage Hub**. Read this BLUEPRINT.md, ARCHITECTURE.md, SPACE.md, all system files, the L1 Coordinate Master Plan, and the `eco-farm-space-blueprint` skill first. Draw the target space in full at 2,800 m² (30,139 ft²), using X 31.680–84.467 m; Y 12.828–65.871 m. Show and label these internal sections: Crop receiving / weighing 160 m²; Covered drying 220 m²; Solar dryer 60 m²; Grain store 400 m²; Rice mill 200 m²; Feed mill 270 m²; Oil press 90 m²; Seed bank 90 m²; Cold room + packhouse 300 m²; Clean milk/egg/fish handling 170 m²; Workshop + spares 260 m²; Silage/hay/feed logistics 280 m²; Internal circulation / fire separation / utilities 300 m². Include north arrow, scale/status, legend, access, drainage/water, electrical/lighting, CCTV/security/safety layers as applicable. Show only small grey/context strips on the four sides: north = vegetable/greenhouse zone across almost the entire north edge, with a very narrow fodder edge at the far east; south = perimeter fire/service road; east = energy & clean-water control zone; west = internal access/buffer strip. Do not fully draw neighboring spaces. Mark every unapproved internal dimension **PROVISIONAL**.

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
