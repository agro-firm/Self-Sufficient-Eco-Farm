# Self-Sufficient Eco Farm

Repository authority for designing and implementing a **5.5-hectare self-sufficient eco-farm**.

## Master basis

- **55,000 m² = 5.5 ha**
- Planning rectangle: **250 m × 220 m**
- CAD planning frame: **250,000 mm × 220,000 mm**
- Origin: south-west corner `(0,0)`
- Continuous perimeter canal; **no separate central fish pond**
- Clean/dirty traffic and wastewater separation
- Fodder-first livestock capacity
- Rooftop solar + battery + biogas backup
- On-site grain/rice/feed/cold/storage/repair infrastructure

## Read first

1. [`docs/FULL_MASTER_PLAN_V6_ENGLISH.md`](docs/FULL_MASTER_PLAN_V6_ENGLISH.md)
2. [`docs/FULL_MASTER_PLAN_V6_BANGLA.md`](docs/FULL_MASTER_PLAN_V6_BANGLA.md)
3. [`docs/MASTER_PLAN_SUMMARY.md`](docs/MASTER_PLAN_SUMMARY.md)
4. [`docs/DECISIONS.md`](docs/DECISIONS.md)
5. [`docs/SPATIAL_DESIGN_STANDARD.md`](docs/SPATIAL_DESIGN_STANDARD.md)
6. [`docs/SPACE_REGISTRY.md`](docs/SPACE_REGISTRY.md)
7. [`docs/IMAGE_BLUEPRINT_STANDARD.md`](docs/IMAGE_BLUEPRINT_STANDARD.md)
8. [`docs/SKILL_INDEX.md`](docs/SKILL_INDEX.md)
9. [`AGENTS.md`](AGENTS.md)

## Precision rule

The skill system can work to centimeter/millimeter accuracy **only when those coordinates/dimensions are approved by the coordinate registry or engineering drawings**. Until then, exact-looking values are marked `PROVISIONAL`; images never become dimensional authority.

## Agent skill architecture

Total current skills: **42**.

The skill system is intentionally split into individual physical spaces and cross-farm systems so a future agent cannot silently redesign the farm while working on one task.

### Global control
- `eco-farm-context`
- `eco-farm-precision-layout-visualization`
- `eco-farm-master-planning`
- `eco-farm-quality-gate`

### Individual spaces
- perimeter wall/security
- perimeter canal
- roads/gates/traffic
- house/admin
- playground
- food crops
- fodder bank
- vegetables/greenhouse/nursery
- orchard/pollinators
- ruminants
- poultry/ducks
- processing/storage hub
- grain/rice mill
- feed/silage/hay
- cold chain/packhouse
- workshop/garage
- biogas/compost
- water treatment
- wastewater treatment
- energy/water control
- quarantine/emergency reserve

### Cross-farm systems
- drainage/wastewater
- solar/battery/generator/electrical
- lighting/CCTV/network
- biosecurity/animal health
- security/flood/cyclone/fire resilience
- monitoring/KPI
- procurement/self-sufficiency
- construction/BOQ
- economics/operations

## How an agent must work on one space

Example: cattle shed design.

1. Load `eco-farm-context`.
2. Load `eco-farm-ruminant-space`.
3. Load `eco-farm-fodder-feed`.
4. Load `eco-farm-water-drainage-wastewater`.
5. Load `eco-farm-energy-electrical` if powered systems are involved.
6. Load `eco-farm-precision-layout-visualization` for drawings/images.
7. Finish with `eco-farm-quality-gate`.

The same pattern applies to every other farm space.

## Image/blueprint behavior

Future agents must not redesign the farm merely because an image model prefers another layout. One image = one requested angle. Multi-angle visualization must preserve identical geometry. Dimensioned images must match approved schedules.

## Engineering boundary

This repository is a master-planning/design authority, not a substitute for legal survey, geotechnical design, structural design, hydraulic engineering, electrical protection design, veterinary care, fire engineering, environmental/public-health approvals, or food-safety compliance.
