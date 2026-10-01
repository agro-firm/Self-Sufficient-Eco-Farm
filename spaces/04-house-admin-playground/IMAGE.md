# House, Admin, Playground, Garage & Swimming Pool — IMAGE.md
## Image, Four-Side Context & Multi-Angle Authority

This file controls images of **House, Admin, Playground, Garage & Swimming Pool**. The target space must always dominate the image, while small correctly positioned glimpses of adjacent spaces prove that the farm topology is correct.

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
- [`eco-farm-house-admin-space`](../../.agents/skills/eco-farm-house-admin-space/SKILL.md)
- [`eco-farm-playground-space`](../../.agents/skills/eco-farm-playground-space/SKILL.md)
- [`eco-farm-electrical-lighting-cctv`](../../.agents/skills/eco-farm-electrical-lighting-cctv/SKILL.md)
- [`eco-farm-security-resilience`](../../.agents/skills/eco-farm-security-resilience/SKILL.md)

# 2. TARGET SPACE IDENTITY

- **Parent area:** 2,200 m²
- **L1 / geometry:** X 28.627–63.384 m; Y 143.877–207.172 m
- **Main internal parts:** 2-story duplex-style house/admin; 20×30 m playground; 120 m² garage; 12×5 m concept secured swimming pool; pool deck/safety/equipment; clean arrival/drive; utility/service; drainage/pervious buffers; roof solar PV; CCTV/security/lighting

## Must not show
- kitchen/vegetable garden
- resort lagoon
- heavy workshop
- livestock/manure traffic
- pool touching playground without barrier

# 3. FOUR-SIDE NEIGHBOR CONTEXT RULE

**Critical rule:** When generating one individual-space image, do **not** fully generate all neighboring spaces. The target space should normally occupy about **75–90% of the visual attention**. Show only small neighbor glimpses/edge strips (about **5–15%**) where the camera can see them.

These small side glimpses are required because they prove the target space is placed correctly.

## North context

**Neighbor beside this side:** perimeter fire/service road beyond north edge

**How much to show**
- target space remains the main subject
- show only a small **5–15% contextual slice** of the neighboring side
- the neighbor must be recognizable but not fully designed/rendered
- use the correct edge object: road, field rows, building edge, wall/canal, yard, trees, buffer, etc.
- do not move the target space inward to make room for the context

**Simple prompt**
> Show **House, Admin, Playground, Garage & Swimming Pool** as the main image. Along the north edge, include only a small contextual glimpse of **perimeter fire/service road beyond north edge**, enough to prove correct adjacency. Do not fully render the neighboring space. Preserve the L1 position and target-space geometry.

## South context

**Neighbor beside this side:** clean internal circulation toward vegetable/production areas

**How much to show**
- target space remains the main subject
- show only a small **5–15% contextual slice** of the neighboring side
- the neighbor must be recognizable but not fully designed/rendered
- use the correct edge object: road, field rows, building edge, wall/canal, yard, trees, buffer, etc.
- do not move the target space inward to make room for the context

**Simple prompt**
> Show **House, Admin, Playground, Garage & Swimming Pool** as the main image. Along the south edge, include only a small contextual glimpse of **clean internal circulation toward vegetable/production areas**, enough to prove correct adjacency. Do not fully render the neighboring space. Preserve the L1 position and target-space geometry.

## East context

**Neighbor beside this side:** human-food crop block

**How much to show**
- target space remains the main subject
- show only a small **5–15% contextual slice** of the neighboring side
- the neighbor must be recognizable but not fully designed/rendered
- use the correct edge object: road, field rows, building edge, wall/canal, yard, trees, buffer, etc.
- do not move the target space inward to make room for the context

**Simple prompt**
> Show **House, Admin, Playground, Garage & Swimming Pool** as the main image. Along the east edge, include only a small contextual glimpse of **human-food crop block**, enough to prove correct adjacency. Do not fully render the neighboring space. Preserve the L1 position and target-space geometry.

## West context

**Neighbor beside this side:** clean internal access/buffer strip

**How much to show**
- target space remains the main subject
- show only a small **5–15% contextual slice** of the neighboring side
- the neighbor must be recognizable but not fully designed/rendered
- use the correct edge object: road, field rows, building edge, wall/canal, yard, trees, buffer, etc.
- do not move the target space inward to make room for the context

**Simple prompt**
> Show **House, Admin, Playground, Garage & Swimming Pool** as the main image. Along the west edge, include only a small contextual glimpse of **clean internal access/buffer strip**, enough to prove correct adjacency. Do not fully render the neighboring space. Preserve the L1 position and target-space geometry.

# 4. TRUE TOP-DOWN VIEW

## Composition
- north up
- show the entire target-space boundary
- target space occupies the dominant central area
- show a thin context strip on all four sides where possible
- label/visually distinguish context if blueprint-like
- do not let neighbor strips distort the target-space dimensions

## What must be clear inside the target
- 2-story duplex-style house/admin
- 20×30 m playground
- 120 m² garage
- 12×5 m concept secured swimming pool
- pool deck/safety/equipment
- clean arrival/drive
- utility/service
- drainage/pervious buffers
- roof solar PV
- CCTV/security/lighting

## Detailed prompt
> Generate a true top-down, north-up image of **House, Admin, Playground, Garage & Swimming Pool**. Read IMAGE.md, ARCHITECTURE.md, BLUEPRINT.md, SPACE.md and all linked system files first. Preserve X 28.627–63.384 m; Y 143.877–207.172 m. Show the complete target space with these main parts: 2-story duplex-style house/admin; 20×30 m playground; 120 m² garage; 12×5 m concept secured swimming pool; pool deck/safety/equipment; clean arrival/drive; utility/service; drainage/pervious buffers; roof solar PV; CCTV/security/lighting. Around the target, show only small context strips: north = perimeter fire/service road beyond north edge; south = clean internal circulation toward vegetable/production areas; east = human-food crop block; west = clean internal access/buffer strip. Neighbor context is only for orientation, not a full rendering. Keep the target at 75–90% visual dominance. Do not show kitchen/vegetable garden; resort lagoon; heavy workshop; livestock/manure traffic; pool touching playground without barrier.

# 5. BLUEPRINT / TECHNICAL IMAGE

Use [BLUEPRINT.md](BLUEPRINT.md) and the [blueprint skill](../../.agents/skills/eco-farm-space-blueprint/SKILL.md).

**Blueprint-specific context rule**
- full target plan
- north/south/east/west context shown only as light grey/hatched strips
- label context strips **CONTEXT ONLY**
- show architecture area schedule, access and relevant systems
- unapproved internal dimensions = **PROVISIONAL**

**Simple blueprint prompt**
> Create the official PROVISIONAL L1 blueprint image for **House, Admin, Playground, Garage & Swimming Pool** using BLUEPRINT.md and ARCHITECTURE.md. Draw the target space in full, include its internal m²/ft² sections, and show only small grey context strips for its four neighboring sides. Do not fully draw neighboring spaces.

# 6. FOUR AERIAL OBLIQUE VIEWS

## North-West aerial — camera NW looking SE
Show the **north** and **west** edges as small contextual glimpses:
- north: perimeter fire/service road beyond north edge
- west: clean internal access/buffer strip
The target remains dominant; far east/south context should be minimal.

**Simple prompt**
> NW aerial oblique of **House, Admin, Playground, Garage & Swimming Pool**, looking SE. Target space dominates. Show only a small north-edge glimpse of perimeter fire/service road beyond north edge and a small west-edge glimpse of clean internal access/buffer strip. Keep 2-story duplex-style house/admin; 20×30 m playground; 120 m² garage; 12×5 m concept secured swimming pool; pool deck/safety/equipment; clean arrival/drive consistent with the top view.

## North-East aerial — camera NE looking SW
Show small **north** + **east** context:
- north: perimeter fire/service road beyond north edge
- east: human-food crop block

**Simple prompt**
> NE aerial oblique of **House, Admin, Playground, Garage & Swimming Pool**, looking SW. Keep the target dominant. Show a small north context of perimeter fire/service road beyond north edge and small east context of human-food crop block. Do not redesign neighboring areas.

## South-East aerial — camera SE looking NW
Show small **south** + **east** context:
- south: clean internal circulation toward vegetable/production areas
- east: human-food crop block

**Simple prompt**
> SE aerial oblique of **House, Admin, Playground, Garage & Swimming Pool**, looking NW. Preserve the same permanent layout. Show only a small glimpse of clean internal circulation toward vegetable/production areas on the south edge and human-food crop block on the east edge.

## South-West aerial — camera SW looking NE
Show small **south** + **west** context:
- south: clean internal circulation toward vegetable/production areas
- west: clean internal access/buffer strip

**Simple prompt**
> SW aerial oblique of **House, Admin, Playground, Garage & Swimming Pool**, looking NE. Target space remains the main subject. Show only small side clues of clean internal circulation toward vegetable/production areas and clean internal access/buffer strip.

# 7. FOUR CARDINAL SIDE VIEWS

## North-side view — camera north looking south
- nearest small foreground/context: perimeter fire/service road beyond north edge
- then immediately reveal the target-space north edge
- target fills most of the frame
- far south neighbor should not be fully rendered

**Prompt**
> Ground-level north-side view of **House, Admin, Playground, Garage & Swimming Pool**, camera north looking south. Show only a small foreground cue of perimeter fire/service road beyond north edge, then make House, Admin, Playground, Garage & Swimming Pool dominate the frame. Preserve all internal parts and L1 orientation.

## South-side view — camera south looking north
- foreground/context: clean internal circulation toward vegetable/production areas
- target begins immediately beyond
- use correct south frontage/access

**Prompt**
> Ground-level south-side view of **House, Admin, Playground, Garage & Swimming Pool**, camera south looking north. Show a small contextual foreground of clean internal circulation toward vegetable/production areas, then the full working face of the target space. Do not fully render the neighboring zone.

## East-side view — camera east looking west
- foreground/context: human-food crop block
- target must stay dominant
- west side context only if naturally visible in distance

**Prompt**
> East-side view of **House, Admin, Playground, Garage & Swimming Pool**, camera east looking west. Include only a small east-neighbor glimpse of human-food crop block; preserve the same target-space architecture and internal arrangement.

## West-side view — camera west looking east
- foreground/context: clean internal access/buffer strip
- target begins immediately after that context
- preserve clean/service character of the real west edge

**Prompt**
> West-side view of **House, Admin, Playground, Garage & Swimming Pool**, camera west looking east. Show a small contextual foreground of clean internal access/buffer strip, then make the target space the main subject.

# 8. CLOSE DETAIL / OPERATIONS VIEWS

Close views should focus on one internal part:
- 2-story duplex-style house/admin
- 20×30 m playground
- 120 m² garage
- 12×5 m concept secured swimming pool
- pool deck/safety/equipment
- clean arrival/drive
- utility/service
- drainage/pervious buffers
- roof solar PV
- CCTV/security/lighting

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

> Create a **[VIEW TYPE]** image of **House, Admin, Playground, Garage & Swimming Pool** in the 5.5-hectare Self-Sufficient Eco Farm. Read the target IMAGE.md, ARCHITECTURE.md, BLUEPRINT.md, SPACE.md, engineering-system files, L1 Coordinate Master Plan and relevant skills first. Preserve X 28.627–63.384 m; Y 143.877–207.172 m. The target space must dominate the image and include 2-story duplex-style house/admin; 20×30 m playground; 120 m² garage; 12×5 m concept secured swimming pool; pool deck/safety/equipment; clean arrival/drive; utility/service; drainage/pervious buffers; roof solar PV; CCTV/security/lighting. Show only small contextual glimpses of neighboring spaces, not full neighboring designs: north = perimeter fire/service road beyond north edge; south = clean internal circulation toward vegetable/production areas; east = human-food crop block; west = clean internal access/buffer strip. Neighbor context should normally be about 5–15% of the visible edge/context. Preserve the same permanent geometry across every angle. Do not show kitchen/vegetable garden; resort lagoon; heavy workshop; livestock/manure traffic; pool touching playground without barrier. One image = one angle.

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
