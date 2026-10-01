# Perimeter Canal — Blueprint Authority

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

- **Space:** Perimeter Canal
- **Parent area:** 5,400 m² / 58,125 ft²
- **Geometry:** continuous ring, planning water width about 5.996 m between the security band and perimeter fire/service road
- **L1:** outer canal control at ~1.931 m inset; inner canal control at ~7.927 m inset
- **Status:** PROVISIONAL L1 unless a later approved drawing supersedes it

## Actual blueprint functional schedule

| ID | Blueprint section | Area | Function |
|---|---|---:|---|
| B01 | Grow-out fish sections | 3,600 m² / 38,750 ft² | main fish-production water |
| B02 | Nursery / hapa management sections | 500 m² / 5,382 ft² | fingerling/nursery control |
| B03 | Irrigation + fire-water intake sections | 300 m² / 3,229 ft² | screened withdrawal/fire suction |
| B04 | Overflow / spillway / sluice section | 250 m² / 2,691 ft² | hydraulic control |
| B05 | Bridge/crossing influence sections | 300 m² / 3,229 ft² | approved access crossings |
| B06 | Aeration / monitoring / maintenance sections | 450 m² / 4,844 ft² | water-quality and service points |
|  | **Total** | **5,400 m² / 58,125 ft²** |  |

## Four-side context — show only small neighbor strips

A one-space blueprint must draw **this target space in full**. For orientation, show only a **small contextual strip (typically 5–15% of sheet depth)** beyond each visible boundary. Do **not** fully draw the neighboring spaces unless requested.

| Side | Small contextual neighbor to show |
|---|---|
| North | security wall/inspection strip outside + perimeter fire/service road inside |
| South | security wall/inspection strip outside + canal gate/bridge crossings + perimeter fire/service road inside |
| East | security wall/inspection strip outside + service-side perimeter road inside |
| West | security wall/inspection strip outside + clean-side perimeter road inside |

Neighbor strips should be lighter/greyed/hatched and labeled **CONTEXT ONLY — NOT PART OF THIS SPACE**.

## Required blueprint layers / elements

- outer bank/control line
- inner bank/control line
- waterline
- nursery/hapa zones
- screens/sluices
- irrigation intake
- fire-water points
- overflow/spillway
- bridge/culvert crossings
- aeration/monitoring/maintenance points

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
                 [ security wall/inspection strip outside + perimeter fire/service road inside ]
        ┌─────────────────────────────────┐
 WEST   │                                 │   EAST
[security wall/inspection strip outside + clean-side perimeter road inside]  │      Perimeter Canal      │ [security wall/inspection strip outside + service-side perimeter road inside]
        │                                 │
        └─────────────────────────────────┘
                 [ security wall/inspection strip outside + canal gate/bridge crossings + perimeter fire/service road inside ]
                              SOUTH
```

## Blueprint image prompt

> Create a precise technical blueprint of **Perimeter Canal**. Read this BLUEPRINT.md, ARCHITECTURE.md, SPACE.md, all system files, the L1 Coordinate Master Plan, and the `eco-farm-space-blueprint` skill first. Draw the target space in full at 5,400 m² (58,125 ft²), using outer canal control at ~1.931 m inset; inner canal control at ~7.927 m inset. Show and label these internal sections: Grow-out fish sections 3600 m²; Nursery / hapa management sections 500 m²; Irrigation + fire-water intake sections 300 m²; Overflow / spillway / sluice section 250 m²; Bridge/crossing influence sections 300 m²; Aeration / monitoring / maintenance sections 450 m². Include north arrow, scale/status, legend, access, drainage/water, electrical/lighting, CCTV/security/safety layers as applicable. Show only small grey/context strips on the four sides: north = security wall/inspection strip outside + perimeter fire/service road inside; south = security wall/inspection strip outside + canal gate/bridge crossings + perimeter fire/service road inside; east = security wall/inspection strip outside + service-side perimeter road inside; west = security wall/inspection strip outside + clean-side perimeter road inside. Do not fully draw neighboring spaces. Mark every unapproved internal dimension **PROVISIONAL**.

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
