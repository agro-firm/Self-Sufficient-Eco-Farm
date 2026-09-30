# Quarantine & Emergency Reserve — Detailed Description

## What this space does

- new-animal quarantine
- sick-animal isolation
- examination/handling
- disinfection
- emergency reserve

## Why it is placed here

Independent controlled-access buffer between clean utility/processing functions and main bird/livestock systems.

## Main dependencies

- [`eco-farm-quarantine-space`](../../.agents/skills/eco-farm-quarantine-space/SKILL.md)
- [`eco-farm-biosecurity-animal-health`](../../.agents/skills/eco-farm-biosecurity-animal-health/SKILL.md)
- [`eco-farm-security-resilience`](../../.agents/skills/eco-farm-security-resilience/SKILL.md)

## Interfaces

### Required / useful neighbors
- Energy/water west
- Poultry east
- Fodder north
- Perimeter service road south

### Controlled / prohibited interfaces
- main herd direct mixing
- clean family route
- shared dirty tools
- uncontrolled drainage

## Utility dependencies

- independent water
- separate drainage
- lighting
- disinfection point
- communications

## Drainage / wastewater principle

Dedicated waste/drain route to appropriate treatment; no connection to clean stormwater.

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
