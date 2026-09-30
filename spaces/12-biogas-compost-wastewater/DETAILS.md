# Biogas, Compost & Wastewater Treatment — Detailed Description

## What this space does

- manure receiving
- solid separation
- digester
- gas handling
- digestate
- composting
- wastewater treatment

## Why it is placed here

Dirty-resource recovery endpoint on far service side, immediately beside the main manure source.

## Main dependencies

- [`eco-farm-biogas-compost-space`](../../.agents/skills/eco-farm-biogas-compost-space/SKILL.md)
- [`eco-farm-biogas-compost-nutrients`](../../.agents/skills/eco-farm-biogas-compost-nutrients/SKILL.md)
- [`eco-farm-wastewater-treatment-space`](../../.agents/skills/eco-farm-wastewater-treatment-space/SKILL.md)
- [`eco-farm-water-drainage-wastewater`](../../.agents/skills/eco-farm-water-drainage-wastewater/SKILL.md)

## Interfaces

### Required / useful neighbors
- Ruminants west
- Fodder north
- Perimeter service road south/east

### Controlled / prohibited interfaces
- family/playground proximity
- ignition sources
- raw discharge to canal
- clean food traffic

## Utility dependencies

- gas piping
- generator interface
- process water
- pumps
- monitoring
- treated reuse lines

## Drainage / wastewater principle

All dirty flows stay contained; sludge/leachate routes explicit; no untreated discharge to canal.

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
