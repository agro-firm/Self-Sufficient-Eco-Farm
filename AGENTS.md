# Agent Instructions

Before significant work in this repository:

1. Read `docs/MASTER_PLAN_SUMMARY.md`.
2. Read `docs/DECISIONS.md`.
3. Read `.agents/skills/eco-farm-context/SKILL.md`.
4. Load only the specialized skills relevant to the task.
5. Run `.agents/skills/eco-farm-quality-gate/SKILL.md` before finalizing work.

## Non-negotiable current decisions

- Planning area: **5.5 ha = 55,000 m²**.
- Planning rectangle: **250 m × 220 m**.
- There is **no separate fish pond** in the base plan.
- The continuous perimeter canal is used for fish, flood retention, irrigation reserve, fire water, and security separation.
- Clean stormwater, human wastewater, animal wastewater, processing wastewater, and oily workshop water are separate systems.
- Animal numbers are constrained by measured feed and waste-treatment capacity.
- Rooftop solar is preferred before using prime crop land.
- Human/family, clean food, animal/dirty, and industrial/service traffic are separated.
- Exact construction dimensions/capacities require site-specific engineering before construction.

Do not silently change these decisions. Record proposed changes in `docs/DECISIONS.md`.

## Precision and image rule

Before any blueprint, dimensioned plan, 3D model, or farm image:
1. Read `docs/SPATIAL_DESIGN_STANDARD.md`.
2. Read `docs/SPACE_REGISTRY.md`.
3. Read `docs/IMAGE_BLUEPRINT_STANDARD.md`.
4. Read the relevant individual space skill(s).
5. Never invent centimeter/mm precision that is not yet approved.
6. Preserve the same farm geometry across all image angles.

## L1 coordinate authority

Before any farm-wide layout, blueprint, rendering, or space-placement task, read `docs/COORDINATE_MASTER_PLAN_L1.md`. Use its zone rectangles and gate positions consistently. Do not move zones merely to improve image composition.

## Per-space documentation rule

Before designing or modifying a physical farm area:
1. Read `spaces/README.md`.
2. Read that space folder's `README.md`.
3. Read its `ARCHITECTURE.md`, `SPACE.md`, `DESIGN.md`, `UTILITIES.md`, and `DETAILS.md`.
4. For images/blueprints, also read `IMAGE.md`.
5. For operational changes, also read `OPERATIONS.md`.
6. Then load the linked agent skill(s) and finish with `eco-farm-quality-gate`.

## Capacity, production and economics rule

For any question about what a space can produce, how many animals/crops it can support, cost, revenue, savings or business use:
1. Read that space's `CAPACITY.md`.
2. Read `PRODUCTION.md`.
3. Read `INPUTS_OUTPUTS.md`.
4. Read `COSTS.md`.
5. Read `ECONOMICS.md`.
6. Read `BUSINESS.md`.
7. Read `docs/ECONOMIC_ASSUMPTIONS.md`.
8. Keep cash revenue, internal replacement value and avoided-loss value separate.
9. Do not call scenario gross value "profit".

## Per-space engineering system rule

Every physical space must maintain dedicated documents for BLUEPRINT, SPACE_MANAGEMENT, DRAINAGE, WATER_SYSTEM, ELECTRICAL, CCTV_SECURITY, LIGHTING, and SAFETY. The content is space-specific; do not copy the house system literally into crops, animals, canal, processing, or utilities.
