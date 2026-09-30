# Agro-Processing & Storage Hub — Detailed Description

## What this space does

- crop receiving/drying
- grain storage
- rice milling
- feed milling
- oil pressing
- seed bank
- cold chain
- clean food handling
- workshop
- feed logistics

## Why it is placed here

One compact support hub with hard internal separation between dusty, clean-food, wet, cold, hot-work and dry-fire-load functions.

## Main dependencies

- [`eco-farm-processing-storage-space`](../../.agents/skills/eco-farm-processing-storage-space/SKILL.md)
- [`eco-farm-processing-storage`](../../.agents/skills/eco-farm-processing-storage/SKILL.md)
- [`eco-farm-grain-rice-mill-space`](../../.agents/skills/eco-farm-grain-rice-mill-space/SKILL.md)
- [`eco-farm-feed-silage-hay-space`](../../.agents/skills/eco-farm-feed-silage-hay-space/SKILL.md)
- [`eco-farm-cold-chain-packhouse-space`](../../.agents/skills/eco-farm-cold-chain-packhouse-space/SKILL.md)
- [`eco-farm-workshop-garage-space`](../../.agents/skills/eco-farm-workshop-garage-space/SKILL.md)

## Interfaces

### Required / useful neighbors
- West access/service strip
- Energy/water east
- Vegetables north
- Perimeter service road south

### Controlled / prohibited interfaces
- manure route through clean handling
- dust into cold/clean areas
- hot work near hay/grain dust
- uncontrolled oily drainage

## Utility dependencies

- three-phase/critical power as required
- clean/food water
- process drains
- data/monitoring
- fire protection

## Drainage / wastewater principle

Source-separate clean food washwater and workshop oily water; oily water goes through separator/hazardous route.

## Main risks

- loss of allocated area to unrelated uses
- cross-contamination between clean and dirty systems
- flood/cyclone damage
- poor maintenance access
- unplanned utility crossings
- future expansion without feed/water/energy/waste capacity checks

## Verification checklist

- [ ] Area remains within parent allocation
- [ ] L1 position is unchanged
- [ ] Required access is clear
- [ ] Drainage path is explicit
- [ ] Power/water/data needs are explicit
- [ ] Fire/emergency access is explicit
- [ ] Neighbor conflicts are checked
- [ ] Image/blueprint matches the master plan
