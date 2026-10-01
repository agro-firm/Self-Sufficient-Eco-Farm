# Perimeter Roads, Gates & Fire Access — Blueprint Authority

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

- **Space:** Perimeter Roads, Gates & Fire Access
- **Parent area:** 4,200 m² / 45,208 ft²
- **Geometry:** continuous perimeter fire/service ring averaging about 4.901 m plus gate approaches, shoulders and drainage
- **L1:** between canal inner control ~7.927 m inset and internal-core control ~12.828 m inset
- **Status:** PROVISIONAL L1 unless a later approved drawing supersedes it

## Actual blueprint functional schedule

| ID | Blueprint section | Area | Function |
|---|---|---:|---|
| B01 | Main perimeter road surface | 3,300 m² / 35,521 ft² | continuous fire/service circulation |
| B02 | Gate + bridge approaches | 350 m² / 3,767 ft² | main/service gate approaches |
| B03 | Turning / lay-by pockets | 200 m² / 2,153 ft² | emergency/service maneuvering |
| B04 | Edge drains / shoulders | 250 m² / 2,691 ft² | road runoff and safety edge |
| B05 | Pedestrian / signage / utility crossing reserve | 100 m² / 1,076 ft² | crossings and route control |
|  | **Total** | **4,200 m² / 45,208 ft²** |  |

## Four-side context — show only small neighbor strips

A one-space blueprint must draw **this target space in full**. For orientation, show only a **small contextual strip (typically 5–15% of sheet depth)** beyond each visible boundary. Do **not** fully draw the neighboring spaces unless requested.

| Side | Small contextual neighbor to show |
|---|---|
| North | canal outside; north internal farm edge inside |
| South | canal outside; main clean gate at X15–21 m and service/emergency gate at X222–227 m; farm core inside |
| East | canal outside; service-oriented farm core inside |
| West | canal outside; clean access/buffer side inside |

Neighbor strips should be lighter/greyed/hatched and labeled **CONTEXT ONLY — NOT PART OF THIS SPACE**.

## Required blueprint layers / elements

- road edges/centerline
- gate widths
- bridge/culvert geometry
- turning bays
- edge drains
- pedestrian crossings
- utility sleeves
- fire-route signage

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
                 [ canal outside; north internal farm edge inside ]
        ┌─────────────────────────────────┐
 WEST   │                                 │   EAST
[canal outside; clean access/buffer side inside]  │      Perimeter Roads, Gates & Fire Access      │ [canal outside; service-oriented farm core inside]
        │                                 │
        └─────────────────────────────────┘
                 [ canal outside; main clean gate at X15–21 m and service/emergency gate at X222–227 m; farm core inside ]
                              SOUTH
```

## Blueprint image prompt

> Create a precise technical blueprint of **Perimeter Roads, Gates & Fire Access**. Read this BLUEPRINT.md, ARCHITECTURE.md, SPACE.md, all system files, the L1 Coordinate Master Plan, and the `eco-farm-space-blueprint` skill first. Draw the target space in full at 4,200 m² (45,208 ft²), using between canal inner control ~7.927 m inset and internal-core control ~12.828 m inset. Show and label these internal sections: Main perimeter road surface 3300 m²; Gate + bridge approaches 350 m²; Turning / lay-by pockets 200 m²; Edge drains / shoulders 250 m²; Pedestrian / signage / utility crossing reserve 100 m². Include north arrow, scale/status, legend, access, drainage/water, electrical/lighting, CCTV/security/safety layers as applicable. Show only small grey/context strips on the four sides: north = canal outside; north internal farm edge inside; south = canal outside; main clean gate at X15–21 m and service/emergency gate at X222–227 m; farm core inside; east = canal outside; service-oriented farm core inside; west = canal outside; clean access/buffer side inside. Do not fully draw neighboring spaces. Mark every unapproved internal dimension **PROVISIONAL**.

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
