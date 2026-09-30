# Human Food Crop Zone — Detailed Description

## What this space does

- rice
- maize
- pulses/legumes
- mustard/sesame
- human food and feed by-products

## Why it is placed here

Maintain a large uninterrupted solar envelope. Seasonal subdivisions may change without moving the outer L1 block.

## Main dependencies

- [`eco-farm-food-crop-space`](../../.agents/skills/eco-farm-food-crop-space/SKILL.md)
- [`eco-farm-crops-horticulture`](../../.agents/skills/eco-farm-crops-horticulture/SKILL.md)
- [`eco-farm-water-drainage-wastewater`](../../.agents/skills/eco-farm-water-drainage-wastewater/SKILL.md)

## Interfaces

### Required / useful neighbors
- House/admin west
- Orchard east
- Perimeter fire road north
- Fodder/vegetable production south

### Controlled / prohibited interfaces
- tall southern obstructions
- dirty wastewater
- random tree planting
- uncontrolled machinery compaction

## Utility dependencies

- irrigation
- field drains/swales
- machinery headlands
- soil monitoring

## Drainage / wastewater principle

Field runoff passes grass/silt controls before any canal inlet.

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
