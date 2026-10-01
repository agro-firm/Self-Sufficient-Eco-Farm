# Perimeter Roads, Gates & Fire Access — IMAGE.md
## Image & Multi-Angle Generation Authority

This file tells an AI, designer, architect, renderer, or human exactly how **Perimeter Roads, Gates & Fire Access** must look from every useful direction while remaining the same physical space in the approved 5.5-hectare farm.

# 1. READ BEFORE GENERATING

Read these linked files **before making any image**.

## Space-specific documents
- [Space README](README.md)
- [Architecture](ARCHITECTURE.md)
- [Space & L1 Coordinates](SPACE.md)
- [Design Rules](DESIGN.md)
- [Detailed Description](DETAILS.md)
- [Utilities & Infrastructure](UTILITIES.md)
- [Blueprint Set](BLUEPRINT.md)
- [Space Management](SPACE_MANAGEMENT.md)
- [Drainage & Stormwater](DRAINAGE.md)
- [Water System](WATER_SYSTEM.md)
- [Electrical System](ELECTRICAL.md)
- [CCTV & Security](CCTV_SECURITY.md)
- [Daylight & Lighting](LIGHTING.md)
- [Safety & Emergency](SAFETY.md)
- [Operations](OPERATIONS.md)
- [Capacity](CAPACITY.md)
- [Production / Service Output](PRODUCTION.md)
- [Inputs & Outputs](INPUTS_OUTPUTS.md)
- [Costs](COSTS.md)
- [Economics](ECONOMICS.md)
- [Business / Value Strategy](BUSINESS.md)

## Farm-wide spatial/image authorities
- [Root Farm SPACE.md](../../SPACE.md)
- [L1 Coordinate Master Plan](../../docs/COORDINATE_MASTER_PLAN_L1.md)
- [Space Registry](../../docs/SPACE_REGISTRY.md)
- [Spatial Design Standard](../../docs/SPATIAL_DESIGN_STANDARD.md)
- [Image & Blueprint Standard](../../docs/IMAGE_BLUEPRINT_STANDARD.md)
- [Master Decisions](../../docs/DECISIONS.md)
- [Farm Master Plan Summary](../../docs/MASTER_PLAN_SUMMARY.md)

## Relevant agent skills
- [`eco-farm-roads-gates-traffic-space`](../../.agents/skills/eco-farm-roads-gates-traffic-space/SKILL.md)
- [`eco-farm-land-civil-zoning`](../../.agents/skills/eco-farm-land-civil-zoning/SKILL.md)
- [`eco-farm-security-resilience`](../../.agents/skills/eco-farm-security-resilience/SKILL.md)
- [`eco-farm-electrical-lighting-cctv`](../../.agents/skills/eco-farm-electrical-lighting-cctv/SKILL.md)

If any image instruction conflicts with a higher authority above, follow the higher authority and correct the image.

# 2. SPACE IDENTITY

- **Space:** Perimeter Roads, Gates & Fire Access
- **Parent area:** 4,200 m²
- **L1 authority:** continuous road ring between canal inner control at about 7.927 m inset and internal-core control at about 12.828 m inset; average width about 4.901 m; main gate X 15–21 m and service gate X 222–227 m on south edge
- **North context:** north perimeter fire/service road between canal and internal farm edge
- **South context:** main clean gate/bridge on south-west and service/emergency gate/bridge on south-east, shown separately when needed
- **East context:** service road beside service/animal/biogas side with edge drains and emergency access
- **West context:** clean-side perimeter road and connection toward the west internal clean spine

## Visual identity — what makes this space recognizable
- continuous fire/service road
- two separate gate approaches
- engineered canal bridge/crossing
- edge drains/shoulders
- tractor/service/emergency turning logic
- road lighting and CCTV where relevant

## Never show
- random roads across crop blocks
- decorative boulevard
- dead-end emergency access
- one combined gate
- road through playground

# 3. GLOBAL CONTINUITY RULES

- Preserve the accepted 5.5 ha master plan and L1 topology.
- One image = one angle/view unless a composite sheet is explicitly requested.
- Rotate the camera, never the farm plan, when a different angle is requested.
- Keep roads, buildings, crop rows, water edges, yards, utilities and neighboring zones in the same positions across all images.
- Use realistic Bangladesh rural/agro-industrial materials, vegetation, climate and scale.
- Show operational logic first: access, drainage, safety, biosecurity, maintenance and utility relationships.
- Do not invent extra land, ponds, buildings, roads or decorative features.

## Coordinate orientation rule
- North, south, east and west always mean the farm's real L1 orientation.
- "Left/right" is relative only to the current camera; never use left/right to relocate a zone.
- If an earlier generated image conflicts with the L1 plan, fix the new image toward the L1 plan.

# 4. TRUE TOP-DOWN VIEW

## Camera
- true vertical or near-orthographic
- north up
- show the full parent space boundary
- show at least a small strip of each relevant neighboring edge so orientation is obvious

## Must show in this specific top view
- continuous fire/service road
- two separate gate approaches
- engineered canal bridge/crossing
- edge drains/shoulders
- tractor/service/emergency turning logic
- road lighting and CCTV where relevant
- north edge context: north perimeter fire/service road between canal and internal farm edge
- south edge context: main clean gate/bridge on south-west and service/emergency gate/bridge on south-east, shown separately when needed
- east edge context: service road beside service/animal/biogas side with edge drains and emergency access
- west edge context: clean-side perimeter road and connection toward the west internal clean spine
- all main paths/roads/service lines that define internal organization
- drainage/water/yard/crop-row structure relevant to the space
- no perspective distortion that makes the zone appear larger/smaller than neighboring blocks

## Detailed top-view prompt
> Generate a **true top-down, north-up** image of **Perimeter Roads, Gates & Fire Access** within the 5.5-hectare Self-Sufficient Eco Farm. Use the approved L1 parent space: continuous road ring between canal inner control at about 7.927 m inset and internal-core control at about 12.828 m inset; average width about 4.901 m; main gate X 15–21 m and service gate X 222–227 m on south edge. Show the complete zone boundary and enough surrounding context to identify all four sides. North: north perimeter fire/service road between canal and internal farm edge. South: main clean gate/bridge on south-west and service/emergency gate/bridge on south-east, shown separately when needed. East: service road beside service/animal/biogas side with edge drains and emergency access. West: clean-side perimeter road and connection toward the west internal clean spine. Inside the space, clearly show continuous fire/service road; two separate gate approaches; engineered canal bridge/crossing; edge drains/shoulders; tractor/service/emergency turning logic; road lighting and CCTV where relevant. Show realistic paths, maintenance access, drainage and utility logic. Do not show random roads across crop blocks; decorative boulevard; dead-end emergency access; one combined gate; road through playground. The result must look like the same physical place that can later be rendered from NW, NE, SE, SW and ground-level views.

# 5. BLUEPRINT / TECHNICAL TOP VIEW

## Use for
- architectural plan
- farm-space blueprint
- measured diagram
- drainage/water overlay
- electrical/CCTV overlay
- production-layout diagram
- access/biosecurity plan

## Must include
- north arrow
- parent-space label and area
- L1 coordinate limits or control references
- internal functional subareas
- entrances/access paths
- utility/drainage interfaces where relevant
- neighboring-zone labels on visible edges
- legend
- revision/status: **PROVISIONAL L1**
- approved dimensions only; all new detailed dimensions marked **PROVISIONAL**

## Blueprint prompt
> Draw a clean technical top-view blueprint of **Perimeter Roads, Gates & Fire Access** using the accepted L1 parent boundary (continuous road ring between canal inner control at about 7.927 m inset and internal-core control at about 12.828 m inset; average width about 4.901 m; main gate X 15–21 m and service gate X 222–227 m on south edge). North must be up. Show each internal function, access path, drainage/utility interface and neighboring edge. Use readable symbols and a legend. Mark all unapproved detail dimensions PROVISIONAL. Do not invent new buildings, ponds, roads or land outside the approved parent area.

# 6. FOUR AERIAL OBLIQUE ANGLES

### North-West aerial oblique

**Camera**
- elevated camera above the north-west side/corner of the parent space
- look south-east
- approximately 25°–45° downward
- wide enough to include the whole space or at least 80–90% plus the two relevant neighboring edges

**Must show**
- north perimeter fire/service road between canal and internal farm edge
- clean-side perimeter road and connection toward the west internal clean spine
- the complete main internal organization of **Perimeter Roads, Gates & Fire Access**
- continuous fire/service road
- two separate gate approaches
- engineered canal bridge/crossing
- edge drains/shoulders
- visible access/service logic
- believable height differences, roof/canopy/yard/field depth
- correct far-side background so the image can be matched to the other angles

**Prompt**
> Generate a photorealistic **North-West aerial oblique** of **Perimeter Roads, Gates & Fire Access**, camera above the north-west side looking south-east. Preserve the exact same L1 space arrangement used in all other views. Near edge: north perimeter fire/service road between canal and internal farm edge. Adjacent edge: clean-side perimeter road and connection toward the west internal clean spine. Clearly show continuous fire/service road; two separate gate approaches; engineered canal bridge/crossing; edge drains/shoulders; tractor/service/emergency turning logic. Include realistic access, drainage, maintenance and safety details. Do not show random roads across crop blocks; decorative boulevard; dead-end emergency access; one combined gate.

### North-East aerial oblique

**Camera**
- elevated camera above the north-east side/corner of the parent space
- look south-west
- approximately 25°–45° downward
- wide enough to include the whole space or at least 80–90% plus the two relevant neighboring edges

**Must show**
- north perimeter fire/service road between canal and internal farm edge
- service road beside service/animal/biogas side with edge drains and emergency access
- the complete main internal organization of **Perimeter Roads, Gates & Fire Access**
- continuous fire/service road
- two separate gate approaches
- engineered canal bridge/crossing
- edge drains/shoulders
- visible access/service logic
- believable height differences, roof/canopy/yard/field depth
- correct far-side background so the image can be matched to the other angles

**Prompt**
> Generate a photorealistic **North-East aerial oblique** of **Perimeter Roads, Gates & Fire Access**, camera above the north-east side looking south-west. Preserve the exact same L1 space arrangement used in all other views. Near edge: north perimeter fire/service road between canal and internal farm edge. Adjacent edge: service road beside service/animal/biogas side with edge drains and emergency access. Clearly show continuous fire/service road; two separate gate approaches; engineered canal bridge/crossing; edge drains/shoulders; tractor/service/emergency turning logic. Include realistic access, drainage, maintenance and safety details. Do not show random roads across crop blocks; decorative boulevard; dead-end emergency access; one combined gate.

### South-East aerial oblique

**Camera**
- elevated camera above the south-east side/corner of the parent space
- look north-west
- approximately 25°–45° downward
- wide enough to include the whole space or at least 80–90% plus the two relevant neighboring edges

**Must show**
- main clean gate/bridge on south-west and service/emergency gate/bridge on south-east, shown separately when needed
- service road beside service/animal/biogas side with edge drains and emergency access
- the complete main internal organization of **Perimeter Roads, Gates & Fire Access**
- continuous fire/service road
- two separate gate approaches
- engineered canal bridge/crossing
- edge drains/shoulders
- visible access/service logic
- believable height differences, roof/canopy/yard/field depth
- correct far-side background so the image can be matched to the other angles

**Prompt**
> Generate a photorealistic **South-East aerial oblique** of **Perimeter Roads, Gates & Fire Access**, camera above the south-east side looking north-west. Preserve the exact same L1 space arrangement used in all other views. Near edge: main clean gate/bridge on south-west and service/emergency gate/bridge on south-east, shown separately when needed. Adjacent edge: service road beside service/animal/biogas side with edge drains and emergency access. Clearly show continuous fire/service road; two separate gate approaches; engineered canal bridge/crossing; edge drains/shoulders; tractor/service/emergency turning logic. Include realistic access, drainage, maintenance and safety details. Do not show random roads across crop blocks; decorative boulevard; dead-end emergency access; one combined gate.

### South-West aerial oblique

**Camera**
- elevated camera above the south-west side/corner of the parent space
- look north-east
- approximately 25°–45° downward
- wide enough to include the whole space or at least 80–90% plus the two relevant neighboring edges

**Must show**
- main clean gate/bridge on south-west and service/emergency gate/bridge on south-east, shown separately when needed
- clean-side perimeter road and connection toward the west internal clean spine
- the complete main internal organization of **Perimeter Roads, Gates & Fire Access**
- continuous fire/service road
- two separate gate approaches
- engineered canal bridge/crossing
- edge drains/shoulders
- visible access/service logic
- believable height differences, roof/canopy/yard/field depth
- correct far-side background so the image can be matched to the other angles

**Prompt**
> Generate a photorealistic **South-West aerial oblique** of **Perimeter Roads, Gates & Fire Access**, camera above the south-west side looking north-east. Preserve the exact same L1 space arrangement used in all other views. Near edge: main clean gate/bridge on south-west and service/emergency gate/bridge on south-east, shown separately when needed. Adjacent edge: clean-side perimeter road and connection toward the west internal clean spine. Clearly show continuous fire/service road; two separate gate approaches; engineered canal bridge/crossing; edge drains/shoulders; tractor/service/emergency turning logic. Include realistic access, drainage, maintenance and safety details. Do not show random roads across crop blocks; decorative boulevard; dead-end emergency access; one combined gate.

# 7. FOUR CARDINAL SIDE / GROUND VIEWS

### North-side view — camera north, looking south

**Camera**
- place camera just north of the parent space
- look toward the opposite cardinal direction
- human eye-level or slightly elevated 2–6 m if needed to read the whole frontage
- do not rotate/mirror the farm geometry

**This angle must show**
- north perimeter fire/service road between canal and internal farm edge
- the near-side boundary and access condition
- at least 3–5 of the space's permanent/functional identity elements
- believable depth through the space toward the far-side neighbor
- drainage/utility/service clues where visible
- scale cues such as people, farm equipment, crop rows, doors, fences or roads appropriate to the space

**Side-view prompt**
> Create the **north-side view — camera north, looking south** of **Perimeter Roads, Gates & Fire Access** in the 5.5-hectare Self-Sufficient Eco Farm. Preserve the accepted L1 layout. north perimeter fire/service road between canal and internal farm edge. Show the parent space as continuous fire/service road with these core features: two separate gate approaches; engineered canal bridge/crossing; edge drains/shoulders; tractor/service/emergency turning logic. Keep neighboring zones and access in their correct positions. Avoid random roads across crop blocks; decorative boulevard; dead-end emergency access. Use realistic Bangladesh farm materials, scale, drainage, safety and working conditions.

### South-side view — camera south, looking north

**Camera**
- place camera just south of the parent space
- look toward the opposite cardinal direction
- human eye-level or slightly elevated 2–6 m if needed to read the whole frontage
- do not rotate/mirror the farm geometry

**This angle must show**
- main clean gate/bridge on south-west and service/emergency gate/bridge on south-east, shown separately when needed
- the near-side boundary and access condition
- at least 3–5 of the space's permanent/functional identity elements
- believable depth through the space toward the far-side neighbor
- drainage/utility/service clues where visible
- scale cues such as people, farm equipment, crop rows, doors, fences or roads appropriate to the space

**Side-view prompt**
> Create the **south-side view — camera south, looking north** of **Perimeter Roads, Gates & Fire Access** in the 5.5-hectare Self-Sufficient Eco Farm. Preserve the accepted L1 layout. main clean gate/bridge on south-west and service/emergency gate/bridge on south-east, shown separately when needed. Show the parent space as continuous fire/service road with these core features: two separate gate approaches; engineered canal bridge/crossing; edge drains/shoulders; tractor/service/emergency turning logic. Keep neighboring zones and access in their correct positions. Avoid random roads across crop blocks; decorative boulevard; dead-end emergency access. Use realistic Bangladesh farm materials, scale, drainage, safety and working conditions.

### East-side view — camera east, looking west

**Camera**
- place camera just east of the parent space
- look toward the opposite cardinal direction
- human eye-level or slightly elevated 2–6 m if needed to read the whole frontage
- do not rotate/mirror the farm geometry

**This angle must show**
- service road beside service/animal/biogas side with edge drains and emergency access
- the near-side boundary and access condition
- at least 3–5 of the space's permanent/functional identity elements
- believable depth through the space toward the far-side neighbor
- drainage/utility/service clues where visible
- scale cues such as people, farm equipment, crop rows, doors, fences or roads appropriate to the space

**Side-view prompt**
> Create the **east-side view — camera east, looking west** of **Perimeter Roads, Gates & Fire Access** in the 5.5-hectare Self-Sufficient Eco Farm. Preserve the accepted L1 layout. service road beside service/animal/biogas side with edge drains and emergency access. Show the parent space as continuous fire/service road with these core features: two separate gate approaches; engineered canal bridge/crossing; edge drains/shoulders; tractor/service/emergency turning logic. Keep neighboring zones and access in their correct positions. Avoid random roads across crop blocks; decorative boulevard; dead-end emergency access. Use realistic Bangladesh farm materials, scale, drainage, safety and working conditions.

### West-side view — camera west, looking east

**Camera**
- place camera just west of the parent space
- look toward the opposite cardinal direction
- human eye-level or slightly elevated 2–6 m if needed to read the whole frontage
- do not rotate/mirror the farm geometry

**This angle must show**
- clean-side perimeter road and connection toward the west internal clean spine
- the near-side boundary and access condition
- at least 3–5 of the space's permanent/functional identity elements
- believable depth through the space toward the far-side neighbor
- drainage/utility/service clues where visible
- scale cues such as people, farm equipment, crop rows, doors, fences or roads appropriate to the space

**Side-view prompt**
> Create the **west-side view — camera west, looking east** of **Perimeter Roads, Gates & Fire Access** in the 5.5-hectare Self-Sufficient Eco Farm. Preserve the accepted L1 layout. clean-side perimeter road and connection toward the west internal clean spine. Show the parent space as continuous fire/service road with these core features: two separate gate approaches; engineered canal bridge/crossing; edge drains/shoulders; tractor/service/emergency turning logic. Keep neighboring zones and access in their correct positions. Avoid random roads across crop blocks; decorative boulevard; dead-end emergency access. Use realistic Bangladesh farm materials, scale, drainage, safety and working conditions.

# 8. PRIMARY AND SECONDARY HUMAN-EYE VIEWS

## Primary working view
**Best subject:** main clean gate road approach showing bridge, canal, wall, gate and clean access

**Must show**
- main operational face
- entrance/service relationship
- at least one clear scale reference
- realistic working surfaces/materials
- safety and maintenance access
- enough background context to identify which side of the zone the viewer is standing on

**Prompt**
> Create a realistic human eye-level primary working view of **Perimeter Roads, Gates & Fire Access**. Show main clean gate road approach showing bridge, canal, wall, gate and clean access. Preserve all permanent object positions from the L1 layout and previously approved images. Use a practical working-farm atmosphere, not a staged decorative scene.

## Secondary working view
**Best subject:** service/emergency gate and heavy-service road showing turning and operational width

**Prompt**
> Create a second eye-level view of **Perimeter Roads, Gates & Fire Access** from the complementary working side. Show service/emergency gate and heavy-service road showing turning and operational width. Keep the same structures, rows, roads, yards, water edges and materials as the primary view; only move the camera.

# 9. FUNCTIONAL CLOSE-DETAIL IMAGES

Generate close-detail images for:
- main clean gate/bridge arrival
- service gate heavy-vehicle arrival
- road shoulder/drain/utility-crossing section

For every close-detail:
- keep some local context so it is clearly part of **Perimeter Roads, Gates & Fire Access**
- show realistic maintenance clearance
- show drainage/containment/safety where applicable
- show working wear/cleanliness appropriate to the system
- never turn a technical detail into an unrelated generic stock image

# 10. WALK-THROUGH / MULTIPLE-IMAGE SEQUENCE

When the user asks for a full visual tour, generate separate images in this order:
1. approach/entry side
2. wide overview from primary working side
3. central operational view
4. opposite/service side
5. one or more technical close details
6. optional exit/back view

**Important:** every frame is a separate image. Do not put eight angles inside one single image unless explicitly requested.

# 11. SPECIAL CONDITION VIEWS

## Night / security
- practical road/security lighting only
- visible CCTV/gate/security logic where relevant
- critical operations illuminated, not entertainment lighting
- preserve dark areas where lighting is unnecessary for animals/pollinators

## Monsoon / heavy rain
- show drains/swales/roof runoff/water containment working
- access should remain functional unless a failure scenario is requested
- no random floodwater in clean/critical spaces

## Cyclone / high-wind readiness
- secured roofs/equipment
- trimmed/managed vegetation
- clear emergency/service routes
- no implication that an image alone proves structural certification

## Operations-in-action
Show real work relevant to this space: feeding, harvesting, loading, washing, checking water, inspecting equipment, packing, maintaining or monitoring.

# 12. "ANOTHER SIDE" BEHAVIOR

If the user asks:
- **another side** → choose the next cardinal side not yet shown
- **opposite side** → move camera 180° around the space
- **back side** → show the operational/rear side opposite the primary frontage
- **left side/right side** → translate to a cardinal direction from the current approved camera, then state that direction
- **top view** → true vertical top-down
- **3D top view** → high aerial oblique, not orthographic
- **front view** → main clean gate road approach showing bridge, canal, wall, gate and clean access
- **all angles** → generate separate NW, NE, SE, SW, north, south, east and west images

# 13. MASTER PROMPT TEMPLATE

> Create a **[VIEW TYPE]** image of **Perimeter Roads, Gates & Fire Access** in the 5.5-hectare Self-Sufficient Eco Farm. Read and follow this space's linked README, ARCHITECTURE, SPACE, DESIGN, DETAILS, UTILITIES and the farm L1 Coordinate Master Plan before generating. The accepted parent space is continuous road ring between canal inner control at about 7.927 m inset and internal-core control at about 12.828 m inset; average width about 4.901 m; main gate X 15–21 m and service gate X 222–227 m on south edge. North context: north perimeter fire/service road between canal and internal farm edge. South context: main clean gate/bridge on south-west and service/emergency gate/bridge on south-east, shown separately when needed. East context: service road beside service/animal/biogas side with edge drains and emergency access. West context: clean-side perimeter road and connection toward the west internal clean spine. The space must visibly contain continuous fire/service road; two separate gate approaches; engineered canal bridge/crossing; edge drains/shoulders; tractor/service/emergency turning logic; road lighting and CCTV where relevant. The image must not contain random roads across crop blocks; decorative boulevard; dead-end emergency access; one combined gate; road through playground. Preserve identical permanent geometry across every angle. Show realistic Bangladesh farm materials, climate, scale, drainage, service access, biosecurity and maintenance logic. One image = one angle.

# 14. FINAL IMAGE VALIDATION

- [ ] Correct parent space and L1 placement
- [ ] Correct requested camera direction
- [ ] All four edge relationships remain believable
- [ ] Permanent geometry matches previous approved views
- [ ] Main identity elements are visible
- [ ] Access/service path is plausible
- [ ] Drainage/water logic is plausible
- [ ] Utilities/safety are represented appropriately
- [ ] No prohibited element was introduced
- [ ] No extra pond/building/road/land was invented
- [ ] The image can be matched to the top view and other angles as the same real place
