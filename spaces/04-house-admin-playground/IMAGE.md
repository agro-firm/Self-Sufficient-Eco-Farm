# House, Admin, Playground, Garage & Swimming Pool — IMAGE.md
## Image & Multi-Angle Generation Authority

This file defines how the redesigned 2,200 m² residential/admin compound must look in every image. The same permanent layout must be preserved across top views, blueprints, aerial angles, side views and close details.

# 1. READ BEFORE GENERATING

## Space documents
- [Space README](README.md)
- [Architecture](ARCHITECTURE.md)
- [Space & L1 Coordinates](SPACE.md)
- [Design Rules](DESIGN.md)
- [Detailed Description](DETAILS.md)
- [Utilities](UTILITIES.md)
- [Blueprint Set](BLUEPRINT.md)
- [Space Management](SPACE_MANAGEMENT.md)
- [Drainage & Stormwater](DRAINAGE.md)
- [Water System](WATER_SYSTEM.md)
- [Electrical System](ELECTRICAL.md)
- [CCTV & Security](CCTV_SECURITY.md)
- [Daylight & Lighting](LIGHTING.md)
- [Safety & Emergency](SAFETY.md)
- [House Program](HOUSE_PROGRAM.md)
- [Garage](GARAGE.md)
- [Swimming Pool](SWIMMING_POOL.md)
- [Solar Power](SOLAR_POWER.md)
- [Playground](PLAYGROUND.md)

## Farm-wide authorities
- [Root Farm SPACE.md](../../SPACE.md)
- [L1 Coordinate Master Plan](../../docs/COORDINATE_MASTER_PLAN_L1.md)
- [Space Registry](../../docs/SPACE_REGISTRY.md)
- [Spatial Design Standard](../../docs/SPATIAL_DESIGN_STANDARD.md)
- [Image & Blueprint Standard](../../docs/IMAGE_BLUEPRINT_STANDARD.md)
- [Master Decisions](../../docs/DECISIONS.md)

## Skills
- [`eco-farm-house-admin-space`](../../.agents/skills/eco-farm-house-admin-space/SKILL.md)
- [`eco-farm-playground-space`](../../.agents/skills/eco-farm-playground-space/SKILL.md)
- [`eco-farm-electrical-lighting-cctv`](../../.agents/skills/eco-farm-electrical-lighting-cctv/SKILL.md)
- [`eco-farm-security-resilience`](../../.agents/skills/eco-farm-security-resilience/SKILL.md)

# 2. FIXED SPACE IDENTITY

- parent: **2,200 m²**
- L1: X 28.627–63.384 m; Y 143.877–207.172 m
- north: perimeter road outside block
- west: clean internal access/arrival
- east: human-food crop block
- south: clean internal circulation toward vegetable/production areas

## Must appear
- **2-story modern tropical duplex-style farmhouse/admin building**, not a single-story small bungalow
- residential/admin garage on clean arrival side
- fixed **20 m × 30 m playground**
- secured rectangular family swimming pool, concept **12 m × 5 m**, with deck/barrier/equipment zone
- rooftop solar PV on suitable house/garage roof surfaces
- admin/CCTV/security character
- clean pedestrian paths
- drainage/pervious/rain-garden logic
- practical outdoor lighting/CCTV where the requested view allows

## Must NOT appear
- kitchen/vegetable garden
- luxury resort lagoon/pool
- oversized ornamental lawn
- heavy tractor workshop
- manure/livestock traffic
- pool touching playground without safety separation
- pool backwash draining to canal/crop field
- house or tall decorative trees moved into the food-crop zone

# 3. CONCEPT INTERNAL PLACEMENT

Use this arrangement consistently:
- **west/south-west:** clean arrival, driveway, residential garage
- **west/north-west:** swimming pool + deck + safety barrier
- **center/west-center:** two-story house/admin
- **east:** playground as low-height recreation buffer before food crops
- **roof:** solar PV
- **distributed:** utility/service points, drainage, pervious paving, safety buffers

Exact internal coordinates remain PROVISIONAL until L2, but once an image set adopts a plausible internal arrangement matching this rule, all later angles must preserve it.

# 4. DAYLIGHT BASELINE IMAGE

When the user asks for a normal/default realistic image, use a bright clear **daylight** condition:
- tropical Bangladesh daylight
- readable roof/PV geometry
- realistic shadows
- no excessive cinematic sunset
- show that the 2-story building and landscaping do not dominate/shade the east crop block excessively
- pool water clean and secured
- playground clearly separate
- drainage/pervious areas visible where practical

# 5. TRUE TOP-DOWN VIEW

## Must show every major component
1. two-story house/admin footprint
2. garage
3. driveway/drop-off
4. pool water
5. pool deck/barrier/equipment zone
6. playground
7. pedestrian paths
8. utility/service area
9. drainage/pervious/rain-garden buffers
10. roof solar PV
11. crop block context east
12. clean access context west
13. perimeter-road context north

## Prompt
> Create a true top-down, north-up daylight image of the redesigned **House, Admin, Playground, Garage & Swimming Pool** space in the 5.5-hectare eco farm. Use the L1 parent block X 28.627–63.384 m, Y 143.877–207.172 m. Show a large but efficient two-story modern tropical duplex-style farmhouse/admin building, residential garage at the west/south-west clean arrival side, secured 12×5 m concept swimming pool with deck/barrier at the west/north-west side, fixed 20×30 m playground on the east side, rooftop solar PV, clean pedestrian paths, CCTV/security points, pervious drainage/rain-garden areas and utility service points. The human-food crop block must remain directly east and free from building encroachment. Do not show any kitchen/vegetable garden, heavy workshop, livestock/manure traffic, resort lagoon or oversized lawn.

# 6. TECHNICAL BLUEPRINT TOP VIEW

Use [BLUEPRINT.md](BLUEPRINT.md).

Must be capable of producing:
- A-001 site/space-management plan
- A-101 ground floor
- A-102 first floor
- A-103 roof/solar
- garage/parking plan
- pool/barrier/plant plan
- drainage plan
- water/plumbing plan
- power plan
- lighting plan
- CCTV/data/access plan
- fire/life-safety plan
- playground/hardscape plan

# 7. AERIAL OBLIQUE ANGLES

## North-West — camera NW looking SE
Near side should reveal north edge/perimeter road and west clean access. Pool should be clearly readable on the west/north-west side, the 2-story house central, playground east, crop field beyond east. Garage remains west/south-west.

## North-East — camera NE looking SW
Foreground/near context should show the east crop boundary and north edge. Playground should be the first major low-height residential component near the crop side; house behind/left, pool farther west, garage south-west. This angle must prove the house/pool do not invade the crop zone.

## South-East — camera SE looking NW
Show clean southern internal access, east-side playground, central 2-story house, west-side pool and south-west garage. No heavy service traffic.

## South-West — camera SW looking NE
Best clean-arrival presentation angle. Garage/driveway nearest, house/admin behind/center, pool toward north-west, playground to east, crop background farther east. Show roof PV and CCTV/lighting.

# 8. FOUR CARDINAL SIDE VIEWS

## North-side view — looking south
Show north facade/roof/PV, pool toward west, house center, playground east. Perimeter road is behind camera/near edge. Keep crop zone beyond east side.

## South-side view — looking north
Show clean arrival/drop-off, garage on west side, main house/admin entrance, safe pedestrian route, playground east, pool farther north-west.

## East-side view — looking west
Camera is near the crop-side edge. Playground should be closest/most visible, providing a low-height transition; two-story house behind west of it; pool and garage farther west. No tall screen blocking crops.

## West-side view — looking east
Camera at clean arrival side. Show garage/driveway and pool-side boundary, house/admin as main mass, playground beyond/east. This is the strongest access/security view.

# 9. EYE-LEVEL / WALK-THROUGH IMAGES

Suggested separate images:
1. clean arrival from west
2. garage/drop-off
3. main house/admin entrance
4. admin/CCTV reception side
5. family courtyard/house side
6. secured pool approach
7. pool deck view
8. playground approach
9. playground full view
10. east-side view toward food crops
11. night-security arrival
12. monsoon drainage view

Never combine these into one image unless a contact sheet is explicitly requested.

# 10. CLOSE-DETAIL IMAGES

- duplex entrance/veranda and admin reception
- CCTV/NVR/security control room exterior/interface
- garage with PV/EV-ready provision
- pool barrier/gate/rescue equipment
- pool plant/filter enclosure
- roof PV and lightning/safe maintenance zone
- rainwater downpipe/first-flush/pervious drain
- exterior electrical/lighting/CCTV detail
- playground lighting/shade/seating

# 11. SPECIAL CONDITIONS

## Night
Low-glare path, pool safety, garage, playground and security lighting. No resort lighting.

## Monsoon
Show gutters, downpipes, permeable surfaces, drains, pool overflow control and dry critical electrical/admin areas.

## Cyclone readiness
Show secured roof/PV, protected openings, trimmed trees, clear emergency routes and no loose pool/playground items.

# 12. CONTINUITY RULE

Change the camera, **not the site plan**. Keep house, garage, pool, playground, paths, PV, access and crop boundary in the same positions from every angle.

# 13. MASTER PROMPT

> Create a [VIEW] image of the redesigned **House, Admin, Playground, Garage & Swimming Pool** zone within the 5.5-hectare Self-Sufficient Eco Farm. It is a 2,200 m² L1 parent block at X 28.627–63.384 m and Y 143.877–207.172 m. Use a large two-story modern tropical duplex-style farmhouse/admin building, west/south-west clean driveway and residential garage, west/north-west secured rectangular swimming pool with deck/barrier/plant, east-side fixed 20×30 m playground, rooftop solar PV, CCTV/security, safe lighting, drainage/rain-garden/pervious areas and utility service points. Preserve the east human-food crop boundary and west clean access. No kitchen garden, no heavy workshop, no livestock/manure traffic, no resort lagoon, no oversized ornamental lawn. One image = one angle, and all permanent geometry must remain identical across angles.
