---
name: eco-farm-master-planning
description: Coordinate farm-wide zoning, resource loops, dependencies, phasing, and trade-offs without breaking accepted master-plan decisions.
---

# Eco-Farm Master Planning

## Workflow
1. Start from the authoritative 55,000 m² allocation.
2. Reconcile the nested perimeter geometry first: ~1.93 m security/inspection gross band, ~6 m canal ring, ~4.9 m perimeter fire/service road, then the internal core.
3. Map clean, dirty, family, food, industrial, emergency, and utility flows; count internal access spines inside the 3,000 m² internal-access/buffer allocation.
4. Check sunlight, flood level, roads, drainage, wind/cyclone exposure, and fire access.
5. Trace water, feed, manure, nutrients, energy, crop by-products, storage, waste, and emergency reserves.
6. Quantify land gained/lost by every proposed change.
7. Verify that total allocation remains exactly 55,000 m² and that subspace schedules do not exceed their parent zones.
8. Identify what must be revalidated if one zone changes.
9. Produce benefits, risks, dependencies, and evidence gaps.

## Guardrails
- No decorative feature may consume critical productive/safety space without an explicit trade-off.
- No zone may block emergency access.
- Do not solve one subsystem by exporting harm to another.

## L1 layout authority

Use `docs/COORDINATE_MASTER_PLAN_L1.md` as the current zone-placement authority. A proposal that moves a zone outside its L1 rectangle is a master-plan change and must update `docs/DECISIONS.md`, the area budget, adjacency review, and quality gate.
