# Energy & Clean-Water Control — Detailed Description

## What this space does

- battery/inverter
- main electrical distribution
- water treatment
- pump controls
- monitoring
- critical utilities

## Why it is placed here

Raised critical utility hub with physical separation between wet water-process spaces and electrical/battery spaces.

## Main dependencies

- [`eco-farm-energy-water-control-space`](../../.agents/skills/eco-farm-energy-water-control-space/SKILL.md)
- [`eco-farm-energy-electrical`](../../.agents/skills/eco-farm-energy-electrical/SKILL.md)
- [`eco-farm-electrical-lighting-cctv`](../../.agents/skills/eco-farm-electrical-lighting-cctv/SKILL.md)
- [`eco-farm-water-treatment-space`](../../.agents/skills/eco-farm-water-treatment-space/SKILL.md)

## Interfaces

### Required / useful neighbors
- Processing west
- Quarantine east
- Perimeter service road south
- Vegetables north

### Controlled / prohibited interfaces
- flood-prone low point
- wet electrical mixing
- manure concentration
- uncontrolled public access

## Utility dependencies

- solar/battery/generator interconnection
- MDB
- water treatment
- pumps
- communications
- fire safety

## Drainage / wastewater principle

Wet treatment rooms use separate drains; live electrical spaces remain dry and above flood risk.

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
