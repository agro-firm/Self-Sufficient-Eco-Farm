# L1 Coordinate Master Plan

**Revision:** L1-2026-09-30-A  
**Status:** PROVISIONAL L1  
**Authority:** Repository planning / blueprints / generated images  
**Not authority for:** legal boundary, construction staking, structural foundations, invert levels, flood levels, or final utility installation

## Coordinate system

- Origin: south-west plot corner = **(0.000, 0.000) m**
- East = **+X**
- North = **+Y**
- Plot = **250.000 m × 220.000 m**
- CAD frame = **250,000 mm × 220,000 mm**

All values below are planning coordinates derived from the approved area budget. Survey control will supersede them at L2/L3.

## 1. Nested perimeter control rectangles

The ring widths below are derived mathematically so the approved area budget closes exactly.

| Control | X-min | X-max | Y-min | Y-max | Derived function |
|---|---:|---:|---:|---:|---|
| Legal/planning plot | 0.000 | 250.000 | 0.000 | 220.000 | 55,000 m² |
| Security/inspection inner control | 1.931 | 248.069 | 1.931 | 218.069 | Leaves 1,800 m² outer security/inspection allocation |
| Canal inner control | 7.927 | 242.073 | 7.927 | 212.073 | Adds 5,400 m² canal ring |
| Internal-core / road inner control | 12.828 | 237.172 | 12.828 | 207.172 | Adds 4,200 m² perimeter fire/service road; leaves 43,600 m² core |

Unrounded derived insets:
- security/inspection = **1.930756687 m**
- canal width = **5.996208309 m**
- fire/service road = **4.900927927 m**

These unrounded values reconcile the areas exactly; drawing labels may show 1.931 / 5.996 / 4.901 m.

## 2. Internal horizontal bands

| Band | Y-min | Y-max | Height | Allocated area |
|---|---:|---:|---:|---:|
| South service/animal band | 12.828 | 65.871 | 53.043 m | 11,900 m² |
| Middle production band | 65.871 | 143.877 | 78.005 m | 17,500 m² |
| North clean/food/family band | 143.877 | 207.172 | 63.296 m | 14,200 m² |

The 3,000 m² internal-access/buffer allocation is split as 1,000 m² in each band along the west side.

## 3. Zone coordinate registry

### South service / animal band

| Zone | X-min | X-max | Y-min | Y-max | Width × height | Area |
|---|---:|---:|---:|---:|---|---:|
| Access/buffer S | 12.828 | 31.680 | 12.828 | 65.871 | 18.852 × 53.043 m | 1,000 m² |
| Processing/storage | 31.680 | 84.467 | 12.828 | 65.871 | 52.787 × 53.043 m | 2,800 m² |
| Energy/water control | 84.467 | 99.549 | 12.828 | 65.871 | 15.082 × 53.043 m | 800 m² |
| Quarantine/emergency | 99.549 | 118.402 | 12.828 | 65.871 | 18.852 × 53.043 m | 1,000 m² |
| Poultry/duck | 118.402 | 146.680 | 12.828 | 65.871 | 28.279 × 53.043 m | 1,500 m² |
| Ruminants | 146.680 | 207.008 | 12.828 | 65.871 | 60.328 × 53.043 m | 3,200 m² |
| Biogas/compost/wastewater | 207.008 | 237.172 | 12.828 | 65.871 | 30.164 × 53.043 m | 1,600 m² |

### Middle production band

| Zone | X-min | X-max | Y-min | Y-max | Width × height | Area |
|---|---:|---:|---:|---:|---|---:|
| Access/buffer M | 12.828 | 25.648 | 65.871 | 143.877 | 12.820 × 78.005 m | 1,000 m² |
| Vegetables/greenhouse/nursery | 25.648 | 83.336 | 65.871 | 143.877 | 57.689 × 78.005 m | 4,500 m² |
| Fodder bank | 83.336 | 237.172 | 65.871 | 143.877 | 153.836 × 78.005 m | 12,000 m² |

### North clean / food / family band

| Zone | X-min | X-max | Y-min | Y-max | Width × height | Area |
|---|---:|---:|---:|---:|---|---:|
| Access/buffer N | 12.828 | 28.627 | 143.877 | 207.172 | 15.799 × 63.296 m | 1,000 m² |
| House/admin/playground | 28.627 | 63.384 | 143.877 | 207.172 | 34.758 × 63.296 m | 2,200 m² |
| Human food crops | 63.384 | 166.077 | 143.877 | 207.172 | 102.693 × 63.296 m | 6,500 m² |
| Orchard/pollinators | 166.077 | 237.172 | 143.877 | 207.172 | 71.095 × 63.296 m | 4,500 m² |

Rounding to 1 mm introduces tiny display differences; authoritative planning **areas** remain the approved values.

## 4. Gates and access

### Main clean gate
- South boundary opening: **X 15.000–21.000 m**
- Clear concept width: **6.000 m**
- Function: family, visitors, clean food/administration route
- Bridge/crossing spans security band and canal
- Aligns with west internal access reserve

### Service / emergency gate
- South boundary opening: **X 222.000–227.000 m**
- Clear concept width: **5.000 m**
- Function: livestock, manure, workshop, heavy machinery, emergency/service
- Direct access to south/east perimeter fire road and dirty/service zones

### West clean internal spine
- Concept road body: **X 16.000–21.000 m**
- Y: **12.828–207.172 m**
- 5.000 m clear road concept
- Entirely contained inside the three west access/buffer strips
- Remaining strip width is reserved for swales, pedestrian separation, utilities, turning/buffer functions

## 5. Adjacency logic

- **House**: north-west clean zone; direct connection to west clean spine.
- **Food crops**: north-central; north edge faces perimeter service ring; no tall southern obstruction.
- **Orchard**: north-east; tall-tree mass stays east/north of primary food-crop block rather than south of it.
- **Vegetables**: middle-west; near clean spine and processing.
- **Fodder**: middle/east; directly north of poultry/ruminants/biogas and therefore short feed-haul distance.
- **Processing**: south-west service band, separated from animals by energy/quarantine/poultry transition zones.
- **Energy/water**: next to processing, away from manure concentration, with direct perimeter service access.
- **Quarantine**: between utilities/processing and poultry; direct south service access.
- **Poultry**: south-central/east, directly below fodder.
- **Ruminants**: south-east-central, directly below fodder and immediately west of biogas.
- **Biogas**: far south-east service end; shortest manure route from ruminants and strong separation from family zone.

## 6. Master diagram

```text
NORTH / Y=220
┌────────────────────────────────────────────────────────────────────┐
│ SECURITY BAND → CANAL → PERIMETER FIRE/SERVICE ROAD              │
│ ┌────────────────────────────────────────────────────────────────┐ │
│ │Access│ House/Admin │      Human Food Crops       │ Orchard     │ │
│ │ N    │ Playground  │                             │ Pollinator  │ │
│ ├──────┼──────────────┴─────────────────────────────┴─────────────┤ │
│ │Access│ Vegetables / Greenhouse │         Fodder Bank           │ │
│ │ M    │ Nursery                │                                │ │
│ ├──────┼───────────────┬────────┬──────────┬─────────┬───────────┤ │
│ │Access│ Processing    │Energy/ │Quarantine│Poultry/ │Ruminants  │Biogas
│ │ S    │ Storage       │Water   │          │Duck     │           │ │
│ └────────────────────────────────────────────────────────────────┘ │
│ SECURITY BAND → CANAL → PERIMETER FIRE/SERVICE ROAD              │
└────────────────────────────────────────────────────────────────────┘
SOUTH / Y=0
Main gate X=15–21 m                         Service gate X=222–227 m
```

## 7. What L1 does and does not approve

L1 approves:
- zone topology
- zone planning areas
- planning X/Y rectangles
- clean/dirty access concept
- gate planning positions
- nested perimeter-ring control lines
- consistent geometry for future images and diagrams

L1 does **not** approve:
- legal property corners
- earthwork levels
- building foundations
- final building footprints inside zones
- drainage invert levels
- pipe/cable routes and sizes
- tree-by-tree coordinates
- structural wall/canal details
- final gate/bridge structural design

Those require survey and L2/L3 engineering.
