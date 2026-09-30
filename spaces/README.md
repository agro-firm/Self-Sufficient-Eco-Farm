# Farm Space Documentation

This directory is the detailed per-space documentation system for the complete 5.5 ha farm.

## Documentation contract

Every major space folder contains:

- `README.md` — basic description, authority links and navigation
- `ARCHITECTURE.md` — spatial/architectural organization and adjacency
- `SPACE.md` — area, L1 coordinates, dimensions and subspace budget
- `DESIGN.md` — design rules, safety and environmental constraints
- `IMAGE.md` — image, render and blueprint generation rules
- `DETAILS.md` — complete component/interface description
- `UTILITIES.md` — power, water, drainage, data, fire and waste interfaces
- `OPERATIONS.md` — operating routines, records and KPIs
- dedicated subspace files where the parent zone contains specialized systems

## Authority order

1. `docs/DECISIONS.md`
2. `docs/COORDINATE_MASTER_PLAN_L1.md`
3. `SPACE.md` at repository root
4. this space folder
5. the linked `.agents/skills/**/SKILL.md`
6. task-specific draft/image

## Space index

| No. | Space | Area | ft² | L1 placement |
|---:|---|---:|---:|---|
| 1 | [Perimeter Canal](01-perimeter-canal/README.md) | 5,400 m² | 58,125 ft² | Outer control: inset 1.931 m. Inner canal control: inset 7.927 m. Derived planning water width ≈ 5.996 m. |
| 2 | [Security Wall, Inspection & Privacy Band](02-security-perimeter/README.md) | 1,800 m² | 19,375 ft² | Plot edge to inner control at 1.931 m average gross inset. Local service/CCTV bays may widen. |
| 3 | [Perimeter Roads, Gates & Fire Access](03-roads-gates-fire-access/README.md) | 4,200 m² | 45,208 ft² | Road ring lies between canal inner control at inset 7.927 m and internal-core control at inset 12.828 m; average width ≈ 4.901 m. Main gate X 15–21 m south edge; service gate X 222–227 m south edge. |
| 4 | [House, Admin, Playground & Kitchen Garden](04-house-admin-playground/README.md) | 2,200 m² | 23,681 ft² | X 28.627–63.384 m; Y 143.877–207.172 m. L1 block ≈34.758 × 63.296 m. |
| 5 | [Human Food Crop Zone](05-human-food-crops/README.md) | 6,500 m² | 69,965 ft² | X 63.384–166.077 m; Y 143.877–207.172 m. L1 block ≈102.693 × 63.296 m. |
| 6 | [Dedicated Fodder Bank](06-fodder-bank/README.md) | 12,000 m² | 129,167 ft² | X 83.336–237.172 m; Y 65.871–143.877 m. L1 block ≈153.836 × 78.005 m. |
| 7 | [Vegetables, Greenhouse & Nursery](07-vegetables-greenhouse-nursery/README.md) | 4,500 m² | 48,438 ft² | X 25.648–83.336 m; Y 65.871–143.877 m. L1 block ≈57.689 × 78.005 m. |
| 8 | [Orchard & Pollinator Zone](08-orchard-pollinators/README.md) | 4,500 m² | 48,438 ft² | X 166.077–237.172 m; Y 143.877–207.172 m. L1 block ≈71.095 × 63.296 m. |
| 9 | [Cattle, Goat & Sheep District](09-ruminants/README.md) | 3,200 m² | 34,445 ft² | X 146.680–207.008 m; Y 12.828–65.871 m. L1 block ≈60.328 × 53.043 m. |
| 10 | [Poultry & Duck District](10-poultry-duck/README.md) | 1,500 m² | 16,146 ft² | X 118.402–146.680 m; Y 12.828–65.871 m. L1 block ≈28.279 × 53.043 m. |
| 11 | [Agro-Processing & Storage Hub](11-processing-storage/README.md) | 2,800 m² | 30,139 ft² | X 31.680–84.467 m; Y 12.828–65.871 m. L1 block ≈52.787 × 53.043 m. |
| 12 | [Biogas, Compost & Wastewater Treatment](12-biogas-compost-wastewater/README.md) | 1,600 m² | 17,222 ft² | X 207.008–237.172 m; Y 12.828–65.871 m. L1 block ≈30.164 × 53.043 m. |
| 13 | [Energy & Clean-Water Control](13-energy-water-control/README.md) | 800 m² | 8,611 ft² | X 84.467–99.549 m; Y 12.828–65.871 m. L1 block ≈15.082 × 53.043 m. |
| 14 | [Quarantine & Emergency Reserve](14-quarantine-emergency/README.md) | 1,000 m² | 10,764 ft² | X 99.549–118.402 m; Y 12.828–65.871 m. L1 block ≈18.852 × 53.043 m. |
| 15 | [Internal Access Spines, Biosecurity Buffers, Headlands & Swales](15-internal-access-buffers/README.md) | 3,000 m² | 32,292 ft² | South strip X 12.828–31.680, Y 12.828–65.871; Middle strip X 12.828–25.648, Y 65.871–143.877; North strip X 12.828–28.627, Y 143.877–207.172. West clean spine concept X 16–21 m across internal core. |

## Important rule

The folder system does **not** create new land allocations. It decomposes the already-approved 55,000 m² plan into maintainable documentation. If a folder needs more area, that is a master-plan change and must be reviewed against every other zone.
