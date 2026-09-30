# Cattle, Goat & Sheep District — Detailed Description

## What this space does

- cattle housing
- goat/sheep housing
- yards
- maternity/youngstock
- feeding/milking
- manure collection

## Why it is placed here

Feed enters from north/clean side; manure exits east/south dirty side toward biogas.

## Main dependencies

- [`eco-farm-ruminant-space`](../../.agents/skills/eco-farm-ruminant-space/SKILL.md)
- [`eco-farm-ruminant-livestock`](../../.agents/skills/eco-farm-ruminant-livestock/SKILL.md)
- [`eco-farm-fodder-feed`](../../.agents/skills/eco-farm-fodder-feed/SKILL.md)
- [`eco-farm-biosecurity-animal-health`](../../.agents/skills/eco-farm-biosecurity-animal-health/SKILL.md)

## Interfaces

### Required / useful neighbors
- Fodder north
- Biogas east
- Poultry west
- Perimeter service road south

### Controlled / prohibited interfaces
- clean packhouse traffic
- playground/family route
- untreated manure runoff
- overstocking

## Utility dependencies

- animal drinking water
- washwater
- lighting/ventilation
- milking/handling power if used
- manure lanes

## Drainage / wastewater principle

Dry scrape first; liquid/manure wash goes to separation/digestion/treatment.

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
