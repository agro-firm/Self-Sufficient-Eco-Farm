# Perimeter Roads, Gates & Fire Access — Space & Coordinates

## Parent allocation

- Area: **4,200 m²**
- Area in square feet: **45,208 ft²**
- Geometry: Continuous perimeter fire/service road ring plus gate/bridge approaches and edge drains.
- L1 coordinate authority: **Road ring lies between canal inner control at inset 7.927 m and internal-core control at inset 12.828 m; average width ≈ 4.901 m. Main gate X 15–21 m south edge; service gate X 222–227 m south edge.**

## Precision status

The outer zone placement is **PROVISIONAL L1** and must be preserved in all repository blueprints and images. Internal centimeter/mm positions are not yet approved unless explicitly documented here or in a dedicated subspace file.

## Space-budget rules

1. Sum all internal subspaces before approval.
2. Do not exceed the parent area.
3. Circulation, maintenance, drains, fire separation and buffers count as real area.
4. Shared utility corridors must be assigned to this zone or the 3,000 m² internal-access/buffer authority.
5. No uncounted "leftover" building may be inserted.

## Required internal functions

- fire access
- service circulation
- gate approaches
- maintenance
- edge drainage

## Neighbor constraints

### Preferred / required neighbors
- Canal outside
- Internal farm core inside
- Internal access/buffer strips connect from west side

### Prohibited or controlled conflicts
- playground through-traffic
- manure traffic on clean packhouse route
- dead-end emergency access
- unverified turning geometry

## Diagram

```mermaid
flowchart LR
    A["Canal outside"]
    S["Perimeter Roads, Gates & Fire Access"]
    B["Internal farm core inside"]
    A --- S --- B
```
