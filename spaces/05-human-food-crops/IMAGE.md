# Human Food Crop Zone — IMAGE.md
## Image, Four-Side Context & Multi-Angle Authority

This file controls images of **Human Food Crop Zone**. The target space must always dominate the image, while small correctly positioned glimpses of adjacent spaces prove that the farm topology is correct.

# 1. READ BEFORE GENERATING

## Target-space documents
- [README](README.md)
- [Architecture + m²/ft² schedule](ARCHITECTURE.md)
- [Space & Coordinates](SPACE.md)
- [Blueprint Authority](BLUEPRINT.md)
- [Space Management](SPACE_MANAGEMENT.md)
- [Design](DESIGN.md)
- [Details](DETAILS.md)
- [Drainage](DRAINAGE.md)
- [Water System](WATER_SYSTEM.md)
- [Electrical](ELECTRICAL.md)
- [CCTV & Security](CCTV_SECURITY.md)
- [Lighting](LIGHTING.md)
- [Safety](SAFETY.md)

## Farm/global authorities
- [Root SPACE.md](../../SPACE.md)
- [L1 Coordinate Master Plan](../../docs/COORDINATE_MASTER_PLAN_L1.md)
- [Space Blueprint Standard](../../docs/SPACE_BLUEPRINT_STANDARD.md)
- [Image & Blueprint Standard](../../docs/IMAGE_BLUEPRINT_STANDARD.md)
- [Space Registry](../../docs/SPACE_REGISTRY.md)
- [Decisions](../../docs/DECISIONS.md)

## Required skills
- [`eco-farm-space-blueprint`](../../.agents/skills/eco-farm-space-blueprint/SKILL.md)
- [`eco-farm-precision-layout-visualization`](../../.agents/skills/eco-farm-precision-layout-visualization/SKILL.md)
- [`eco-farm-food-crop-space`](../../.agents/skills/eco-farm-food-crop-space/SKILL.md)
- [`eco-farm-crops-horticulture`](../../.agents/skills/eco-farm-crops-horticulture/SKILL.md)
- [`eco-farm-water-drainage-wastewater`](../../.agents/skills/eco-farm-water-drainage-wastewater/SKILL.md)

# 2. TARGET SPACE IDENTITY

- **Parent area:** 6,500 m²
- **L1 / geometry:** X 63.384–166.077 m; Y 143.877–207.172 m
- **Main internal parts:** Rice block; Maize block; Pulse/legume block; Oilseed block; Headlands/field access; Irrigation/drainage edges

## Must not show
- orchard trees inside crops
- random sheds
- decorative lawns
- dense shade
- diagonal roads

# 3. FOUR-SIDE NEIGHBOR CONTEXT RULE

**Critical rule:** When generating one individual-space image, do **not** fully generate all neighboring spaces. The target space should normally occupy about **75–90% of the visual attention**. Show only small neighbor glimpses/edge strips (about **5–15%**) where the camera can see them.

These small side glimpses are required because they prove the target space is placed correctly.

## North context

**Neighbor beside this side:** perimeter fire/service road

**How much to show**
- target space remains the main subject
- show only a small **5–15% contextual slice** of the neighboring side
- the neighbor must be recognizable but not fully designed/rendered
- use the correct edge object: road, field rows, building edge, wall/canal, yard, trees, buffer, etc.
- do not move the target space inward to make room for the context

**Simple prompt**
> Show **Human Food Crop Zone** as the main image. Along the north edge, include only a small contextual glimpse of **perimeter fire/service road**, enough to prove correct adjacency. Do not fully render the neighboring space. Preserve the L1 position and target-space geometry.

## South context

**Neighbor beside this side:** vegetable + fodder production band

**How much to show**
- target space remains the main subject
- show only a small **5–15% contextual slice** of the neighboring side
- the neighbor must be recognizable but not fully designed/rendered
- use the correct edge object: road, field rows, building edge, wall/canal, yard, trees, buffer, etc.
- do not move the target space inward to make room for the context

**Simple prompt**
> Show **Human Food Crop Zone** as the main image. Along the south edge, include only a small contextual glimpse of **vegetable + fodder production band**, enough to prove correct adjacency. Do not fully render the neighboring space. Preserve the L1 position and target-space geometry.

## East context

**Neighbor beside this side:** orchard/pollinator zone

**How much to show**
- target space remains the main subject
- show only a small **5–15% contextual slice** of the neighboring side
- the neighbor must be recognizable but not fully designed/rendered
- use the correct edge object: road, field rows, building edge, wall/canal, yard, trees, buffer, etc.
- do not move the target space inward to make room for the context

**Simple prompt**
> Show **Human Food Crop Zone** as the main image. Along the east edge, include only a small contextual glimpse of **orchard/pollinator zone**, enough to prove correct adjacency. Do not fully render the neighboring space. Preserve the L1 position and target-space geometry.

## West context

**Neighbor beside this side:** house/admin/playground/garage/pool zone

**How much to show**
- target space remains the main subject
- show only a small **5–15% contextual slice** of the neighboring side
- the neighbor must be recognizable but not fully designed/rendered
- use the correct edge object: road, field rows, building edge, wall/canal, yard, trees, buffer, etc.
- do not move the target space inward to make room for the context

**Simple prompt**
> Show **Human Food Crop Zone** as the main image. Along the west edge, include only a small contextual glimpse of **house/admin/playground/garage/pool zone**, enough to prove correct adjacency. Do not fully render the neighboring space. Preserve the L1 position and target-space geometry.

# 4. TRUE TOP-DOWN VIEW

## Composition
- north up
- show the entire target-space boundary
- target space occupies the dominant central area
- show a thin context strip on all four sides where possible
- label/visually distinguish context if blueprint-like
- do not let neighbor strips distort the target-space dimensions

## What must be clear inside the target
- Rice block
- Maize block
- Pulse/legume block
- Oilseed block
- Headlands/field access
- Irrigation/drainage edges

## Detailed prompt
> Generate a true top-down, north-up image of **Human Food Crop Zone**. Read IMAGE.md, ARCHITECTURE.md, BLUEPRINT.md, SPACE.md and all linked system files first. Preserve X 63.384–166.077 m; Y 143.877–207.172 m. Show the complete target space with these main parts: Rice block; Maize block; Pulse/legume block; Oilseed block; Headlands/field access; Irrigation/drainage edges. Around the target, show only small context strips: north = perimeter fire/service road; south = vegetable + fodder production band; east = orchard/pollinator zone; west = house/admin/playground/garage/pool zone. Neighbor context is only for orientation, not a full rendering. Keep the target at 75–90% visual dominance. Do not show orchard trees inside crops; random sheds; decorative lawns; dense shade; diagonal roads.

# 5. BLUEPRINT / TECHNICAL IMAGE

Use [BLUEPRINT.md](BLUEPRINT.md) and the [blueprint skill](../../.agents/skills/eco-farm-space-blueprint/SKILL.md).

**Blueprint-specific context rule**
- full target plan
- north/south/east/west context shown only as light grey/hatched strips
- label context strips **CONTEXT ONLY**
- show architecture area schedule, access and relevant systems
- unapproved internal dimensions = **PROVISIONAL**

**Simple blueprint prompt**
> Create the official PROVISIONAL L1 blueprint image for **Human Food Crop Zone** using BLUEPRINT.md and ARCHITECTURE.md. Draw the target space in full, include its internal m²/ft² sections, and show only small grey context strips for its four neighboring sides. Do not fully draw neighboring spaces.

# 6. FOUR AERIAL OBLIQUE VIEWS

## North-West aerial — camera NW looking SE
Show the **north** and **west** edges as small contextual glimpses:
- north: perimeter fire/service road
- west: house/admin/playground/garage/pool zone
The target remains dominant; far east/south context should be minimal.

**Simple prompt**
> NW aerial oblique of **Human Food Crop Zone**, looking SE. Target space dominates. Show only a small north-edge glimpse of perimeter fire/service road and a small west-edge glimpse of house/admin/playground/garage/pool zone. Keep Rice block; Maize block; Pulse/legume block; Oilseed block; Headlands/field access; Irrigation/drainage edges consistent with the top view.

## North-East aerial — camera NE looking SW
Show small **north** + **east** context:
- north: perimeter fire/service road
- east: orchard/pollinator zone

**Simple prompt**
> NE aerial oblique of **Human Food Crop Zone**, looking SW. Keep the target dominant. Show a small north context of perimeter fire/service road and small east context of orchard/pollinator zone. Do not redesign neighboring areas.

## South-East aerial — camera SE looking NW
Show small **south** + **east** context:
- south: vegetable + fodder production band
- east: orchard/pollinator zone

**Simple prompt**
> SE aerial oblique of **Human Food Crop Zone**, looking NW. Preserve the same permanent layout. Show only a small glimpse of vegetable + fodder production band on the south edge and orchard/pollinator zone on the east edge.

## South-West aerial — camera SW looking NE
Show small **south** + **west** context:
- south: vegetable + fodder production band
- west: house/admin/playground/garage/pool zone

**Simple prompt**
> SW aerial oblique of **Human Food Crop Zone**, looking NE. Target space remains the main subject. Show only small side clues of vegetable + fodder production band and house/admin/playground/garage/pool zone.

# 7. FOUR CARDINAL SIDE VIEWS

## North-side view — camera north looking south
- nearest small foreground/context: perimeter fire/service road
- then immediately reveal the target-space north edge
- target fills most of the frame
- far south neighbor should not be fully rendered

**Prompt**
> Ground-level north-side view of **Human Food Crop Zone**, camera north looking south. Show only a small foreground cue of perimeter fire/service road, then make Human Food Crop Zone dominate the frame. Preserve all internal parts and L1 orientation.

## South-side view — camera south looking north
- foreground/context: vegetable + fodder production band
- target begins immediately beyond
- use correct south frontage/access

**Prompt**
> Ground-level south-side view of **Human Food Crop Zone**, camera south looking north. Show a small contextual foreground of vegetable + fodder production band, then the full working face of the target space. Do not fully render the neighboring zone.

## East-side view — camera east looking west
- foreground/context: orchard/pollinator zone
- target must stay dominant
- west side context only if naturally visible in distance

**Prompt**
> East-side view of **Human Food Crop Zone**, camera east looking west. Include only a small east-neighbor glimpse of orchard/pollinator zone; preserve the same target-space architecture and internal arrangement.

## West-side view — camera west looking east
- foreground/context: house/admin/playground/garage/pool zone
- target begins immediately after that context
- preserve clean/service character of the real west edge

**Prompt**
> West-side view of **Human Food Crop Zone**, camera west looking east. Show a small contextual foreground of house/admin/playground/garage/pool zone, then make the target space the main subject.

# 8. CLOSE DETAIL / OPERATIONS VIEWS

Close views should focus on one internal part:
- Rice block
- Maize block
- Pulse/legume block
- Oilseed block
- Headlands/field access
- Irrigation/drainage edges

For close-ups, include only enough neighboring/background context to identify location. Do not turn close-detail images into whole-farm scenes.

# 9. CONTINUITY ACROSS IMAGES

When making another angle:
1. use the same internal arrangement from the approved top view/blueprint
2. keep all permanent objects in the same positions
3. rotate the camera, not the site plan
4. keep neighbor sides exactly north/south/east/west as defined here
5. neighbor context remains small and secondary
6. if a prior image conflicts with the blueprint/L1 plan, correct toward the blueprint/L1 authority

# 10. DAY / NIGHT / MONSOON / SPECIAL CONDITIONS

- **Daylight default:** clear realistic Bangladesh daylight; architecture/rows/equipment easy to read
- **Night:** only practical safety/security/task lighting
- **Monsoon:** show drainage/water-management systems working
- **Cyclone readiness:** show secured roofs/equipment/vegetation and access
- **Operations:** show real work appropriate to the target space without changing layout

# 11. MASTER IMAGE PROMPT

> Create a **[VIEW TYPE]** image of **Human Food Crop Zone** in the 5.5-hectare Self-Sufficient Eco Farm. Read the target IMAGE.md, ARCHITECTURE.md, BLUEPRINT.md, SPACE.md, engineering-system files, L1 Coordinate Master Plan and relevant skills first. Preserve X 63.384–166.077 m; Y 143.877–207.172 m. The target space must dominate the image and include Rice block; Maize block; Pulse/legume block; Oilseed block; Headlands/field access; Irrigation/drainage edges. Show only small contextual glimpses of neighboring spaces, not full neighboring designs: north = perimeter fire/service road; south = vegetable + fodder production band; east = orchard/pollinator zone; west = house/admin/playground/garage/pool zone. Neighbor context should normally be about 5–15% of the visible edge/context. Preserve the same permanent geometry across every angle. Do not show orchard trees inside crops; random sheds; decorative lawns; dense shade; diagonal roads. One image = one angle.

# 12. VALIDATION

- [ ] target space dominates
- [ ] internal architecture matches ARCHITECTURE.md
- [ ] top/blueprint matches BLUEPRINT.md
- [ ] north neighbor is correct
- [ ] south neighbor is correct
- [ ] east neighbor is correct
- [ ] west neighbor is correct
- [ ] neighboring spaces are only small context, not fully rendered
- [ ] no mirroring/swapping of cardinal sides
- [ ] all permanent objects remain consistent across angles
- [ ] prohibited features are absent
