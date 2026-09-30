# Eco-Farm Agent Skills

This is the **single skill index and routing page** for the Self-Sufficient Eco Farm.

The old `docs/SKILL_INDEX.md` is retained only as a redirect. All agents should use this file as the current skill directory.

## Required workflow

1. Start with [`eco-farm-context`](skills/eco-farm-context/SKILL.md).
2. Read [`docs/MASTER_PLAN_SUMMARY.md`](../docs/MASTER_PLAN_SUMMARY.md), [`docs/DECISIONS.md`](../docs/DECISIONS.md), and [`SPACE.md`](../SPACE.md).
3. Load the relevant physical-space skill(s).
4. Load the relevant cross-farm system skill(s).
5. For blueprints, dimensions, or images, load [`eco-farm-precision-layout-visualization`](skills/eco-farm-precision-layout-visualization/SKILL.md).
6. Finish with [`eco-farm-quality-gate`](skills/eco-farm-quality-gate/SKILL.md).

## Precision authorities

- [Spatial Design Standard](../docs/SPATIAL_DESIGN_STANDARD.md)
- [Space Registry](../docs/SPACE_REGISTRY.md)
- [Image & Blueprint Standard](../docs/IMAGE_BLUEPRINT_STANDARD.md)
- [SPACE.md](../SPACE.md)

The farm planning frame is **250,000 mm × 220,000 mm**. Exact centimeter/mm values are binding only when approved by the coordinate registry or engineering drawings. Otherwise they must be marked **PROVISIONAL**.

## Skill directory

### Global control

| Skill | Purpose |
|---|---|
| [`eco-farm-context`](skills/eco-farm-context/SKILL.md) | Establish the authoritative farm dimensions, decisions, boundaries, evidence, and specialist skills before significant farm work. |
| [`eco-farm-precision-layout-visualization`](skills/eco-farm-precision-layout-visualization/SKILL.md) | Control centimeter/mm-accurate layout work, coordinate authority, blueprints, renders, and image prompts so visual outputs cannot redesign the farm. |
| [`eco-farm-master-planning`](skills/eco-farm-master-planning/SKILL.md) | Coordinate farm-wide zoning, resource loops, dependencies, phasing, and trade-offs without breaking accepted master-plan decisions. |
| [`eco-farm-quality-gate`](skills/eco-farm-quality-gate/SKILL.md) | Review farm plans, calculations, images, BOQs, and implementation changes for authority conflicts, missing dependencies, unsafe assumptions, and cross-system harm. |

### Physical-space skills

| Skill | Purpose |
|---|---|
| [`eco-farm-perimeter-wall-security-space`](skills/eco-farm-perimeter-wall-security-space/SKILL.md) | Design the perimeter wall, privacy belt, inspection strip, anti-intrusion features, and interfaces with canal, gates, CCTV, lighting, and emergency access. |
| [`eco-farm-perimeter-canal-space`](skills/eco-farm-perimeter-canal-space/SKILL.md) | Design the continuous perimeter canal as fish habitat, flood retention, irrigation reserve, fire water, and security separation without creating a separate pond. |
| [`eco-farm-roads-gates-traffic-space`](skills/eco-farm-roads-gates-traffic-space/SKILL.md) | Design main gate, service/emergency gate, fire road, primary/secondary roads, pedestrian paths, turning areas, and clean/dirty traffic separation. |
| [`eco-farm-house-admin-space`](skills/eco-farm-house-admin-space/SKILL.md) | Design the clean residential, administration, CCTV/control, first-aid, emergency shelter, parking, and kitchen-garden space. |
| [`eco-farm-playground-space`](skills/eco-farm-playground-space/SKILL.md) | Design the 20 m × 30 m playground and family recreation/assembly area with safe separation from canal, traffic, animals, utilities, and hazards. |
| [`eco-farm-food-crop-space`](skills/eco-farm-food-crop-space/SKILL.md) | Design the open-sun human-food crop block for rice, maize, pulses, and oilseeds with rotations, headlands, machinery, irrigation, and no tall shading elements. |
| [`eco-farm-fodder-bank-space`](skills/eco-farm-fodder-bank-space/SKILL.md) | Design the 12,000 m² fodder bank, harvest lanes, cut-and-carry system, silage crop blocks, and feed-capacity control for livestock. |
| [`eco-farm-vegetable-greenhouse-nursery-space`](skills/eco-farm-vegetable-greenhouse-nursery-space/SKILL.md) | Design open vegetables, greenhouse modules, nursery/mother plants, clean wash points, paths, crop rotations, irrigation, and hygiene. |
| [`eco-farm-orchard-pollinator-space`](skills/eco-farm-orchard-pollinator-space/SKILL.md) | Design the 4,500 m² orchard, mature tree spacing, low-shadow edge strategy, banana/papaya layers, pollinator strips, beehives, access, mulch, and drains. |
| [`eco-farm-ruminant-space`](skills/eco-farm-ruminant-space/SKILL.md) | Design the cattle, goat, and sheep district including sheds, yards, maternity, youngstock, feed alleys, water, manure lanes, ventilation, and biosecurity. |
| [`eco-farm-poultry-duck-space`](skills/eco-farm-poultry-duck-space/SKILL.md) | Design separate layer, broiler, and duck spaces with feed, egg handling, all-in/all-out sanitation, wet-pad drainage, isolation, and biosecurity. |
| [`eco-farm-processing-storage-space`](skills/eco-farm-processing-storage-space/SKILL.md) | Design the complete 2,800 m² agro-processing and storage hub and enforce clean/dirty/dust/wet/fire separation. |
| [`eco-farm-grain-rice-mill-space`](skills/eco-farm-grain-rice-mill-space/SKILL.md) | Design grain receiving, drying, 25–40 t storage, rice mill, bran/husk recovery, dust control, pest control, and human-food/feed/seed segregation. |
| [`eco-farm-feed-silage-hay-space`](skills/eco-farm-feed-silage-hay-space/SKILL.md) | Design feed milling, ingredient segregation, silage bunker, hay barn, roughage reserves, ingredient flow, and species-specific ration preparation. |
| [`eco-farm-cold-chain-packhouse-space`](skills/eco-farm-cold-chain-packhouse-space/SKILL.md) | Design clean produce receiving, wash/sort/pack, cold rooms, milk chilling, egg grading, fish chilling, hygiene zoning, drains, and critical power. |
| [`eco-farm-workshop-garage-space`](skills/eco-farm-workshop-garage-space/SKILL.md) | Design the garage and farm workshop for cars, tractors, implements, charging, repairs, spares, lubricants, washing, drainage, hot work, and service traffic. |
| [`eco-farm-biogas-compost-space`](skills/eco-farm-biogas-compost-space/SKILL.md) | Design manure receiving, solid separation, digester, gas handling, digestate treatment, composting, wastewater interfaces, safety buffer, and nutrient-return routes. |
| [`eco-farm-water-treatment-space`](skills/eco-farm-water-treatment-space/SKILL.md) | Design potable, food-processing, animal-drinking, irrigation, service, and fire-water treatment/storage systems with source-specific testing and protected distribution. |
| [`eco-farm-wastewater-treatment-space`](skills/eco-farm-wastewater-treatment-space/SKILL.md) | Design the physical treatment areas for human sewage, greywater, livestock wastewater, poultry/duck washwater, processing wastewater, sludge, wetlands, and safe reuse/outfall. |
| [`eco-farm-energy-water-control-space`](skills/eco-farm-energy-water-control-space/SKILL.md) | Design the raised critical utility hub for batteries, inverters, switchgear, water treatment, pump controls, monitoring, access, fire safety, and flood resilience. |
| [`eco-farm-quarantine-space`](skills/eco-farm-quarantine-space/SKILL.md) | Design independent animal quarantine/isolation and emergency reserve space with controlled access, drainage, handling, disinfection, and separation from main herds/flocks. |

### System and operations skills

| Skill | Purpose |
|---|---|
| [`eco-farm-land-civil-zoning`](skills/eco-farm-land-civil-zoning/SKILL.md) | Design land zoning, roads, walls, canal interfaces, levels, buffers, circulation, and civil-space reservations. |
| [`eco-farm-crops-horticulture`](skills/eco-farm-crops-horticulture/SKILL.md) | Plan food crops, vegetables, greenhouse, nursery, orchard, pollinators, rotations, sunlight, irrigation, and crop-residue reuse. |
| [`eco-farm-fodder-feed`](skills/eco-farm-fodder-feed/SKILL.md) | Size the fodder bank, feed reserves, silage/hay system, ration inputs, and animal capacity around measured feed availability. |
| [`eco-farm-ruminant-livestock`](skills/eco-farm-ruminant-livestock/SKILL.md) | Plan cattle, goat, and sheep capacity, housing, production, breeding, manure flows, welfare, and expansion gates. |
| [`eco-farm-poultry-duck`](skills/eco-farm-poultry-duck/SKILL.md) | Plan layers, broilers, ducks, housing, feed, egg/meat flows, wet/dry separation, biosecurity, and wastewater handling. |
| [`eco-farm-canal-aquaculture`](skills/eco-farm-canal-aquaculture/SKILL.md) | Manage the perimeter canal as a combined fish, flood-storage, irrigation-reserve, fire-water, and security system. |
| [`eco-farm-water-drainage-wastewater`](skills/eco-farm-water-drainage-wastewater/SKILL.md) | Design separated clean-water, stormwater, human wastewater, animal wastewater, processing wastewater, and oily-water systems. |
| [`eco-farm-biogas-compost-nutrients`](skills/eco-farm-biogas-compost-nutrients/SKILL.md) | Convert manure and suitable organic residues into biogas, compost, digestate, and a measured nutrient-recycling system. |
| [`eco-farm-energy-electrical`](skills/eco-farm-energy-electrical/SKILL.md) | Plan rooftop solar, battery, biogas backup, critical loads, distribution, lighting, CCTV power, earthing, and resilience. |
| [`eco-farm-electrical-lighting-cctv`](skills/eco-farm-electrical-lighting-cctv/SKILL.md) | Design farm-wide electrical distribution routes, road/security lighting, CCTV, network backbone, control room, backup power, and monitoring placement. |
| [`eco-farm-processing-storage`](skills/eco-farm-processing-storage/SKILL.md) | Design the processing and storage hub for grain, rice, feed, oilseed, seed, cold chain, food handling, workshop, and feed reserves. |
| [`eco-farm-biosecurity-animal-health`](skills/eco-farm-biosecurity-animal-health/SKILL.md) | Protect livestock, poultry, ducks, fish, crops, workers, and food areas through quarantine, hygiene, movement controls, vaccination, and disease response. |
| [`eco-farm-security-resilience`](skills/eco-farm-security-resilience/SKILL.md) | Design physical security, CCTV, lighting, fire protection, flood resilience, cyclone resilience, emergency access, and family safety. |
| [`eco-farm-monitoring-kpi`](skills/eco-farm-monitoring-kpi/SKILL.md) | Define farm records, sensors, KPIs, thresholds, audits, and evidence needed to improve production without overloading the ecosystem. |
| [`eco-farm-procurement-self-sufficiency`](skills/eco-farm-procurement-self-sufficiency/SKILL.md) | Minimize external dependency while identifying inputs that should still be purchased for safety, quality, genetics, nutrition, maintenance, and compliance. |
| [`eco-farm-construction-boq`](skills/eco-farm-construction-boq/SKILL.md) | Turn approved master-plan concepts into phased engineering packages, quantities, BOQs, procurement packages, and construction acceptance criteria. |
| [`eco-farm-economics-operations`](skills/eco-farm-economics-operations/SKILL.md) | Model CAPEX, OPEX, production, internal transfer value, external purchases, reserves, maintenance, and phased operational sustainability. |

## Skill selection examples

### Design the cattle area
Use:
- [`eco-farm-context`](skills/eco-farm-context/SKILL.md)
- [`eco-farm-ruminant-space`](skills/eco-farm-ruminant-space/SKILL.md)
- [`eco-farm-ruminant-livestock`](skills/eco-farm-ruminant-livestock/SKILL.md)
- [`eco-farm-fodder-feed`](skills/eco-farm-fodder-feed/SKILL.md)
- [`eco-farm-water-drainage-wastewater`](skills/eco-farm-water-drainage-wastewater/SKILL.md)
- [`eco-farm-energy-electrical`](skills/eco-farm-energy-electrical/SKILL.md)
- [`eco-farm-precision-layout-visualization`](skills/eco-farm-precision-layout-visualization/SKILL.md)
- [`eco-farm-quality-gate`](skills/eco-farm-quality-gate/SKILL.md)

### Make a farm-wide blueprint
Use:
- [`eco-farm-context`](skills/eco-farm-context/SKILL.md)
- [`eco-farm-master-planning`](skills/eco-farm-master-planning/SKILL.md)
- [`eco-farm-land-civil-zoning`](skills/eco-farm-land-civil-zoning/SKILL.md)
- [`eco-farm-precision-layout-visualization`](skills/eco-farm-precision-layout-visualization/SKILL.md)
- all affected space skills
- [`eco-farm-quality-gate`](skills/eco-farm-quality-gate/SKILL.md)

### Make a drainage plan
Use:
- [`eco-farm-water-drainage-wastewater`](skills/eco-farm-water-drainage-wastewater/SKILL.md)
- [`eco-farm-wastewater-treatment-space`](skills/eco-farm-wastewater-treatment-space/SKILL.md)
- [`eco-farm-perimeter-canal-space`](skills/eco-farm-perimeter-canal-space/SKILL.md)
- the relevant source-zone skill(s)
- [`eco-farm-quality-gate`](skills/eco-farm-quality-gate/SKILL.md)

### Make an electrical/CCTV/road-light plan
Use:
- [`eco-farm-energy-electrical`](skills/eco-farm-energy-electrical/SKILL.md)
- [`eco-farm-electrical-lighting-cctv`](skills/eco-farm-electrical-lighting-cctv/SKILL.md)
- [`eco-farm-energy-water-control-space`](skills/eco-farm-energy-water-control-space/SKILL.md)
- [`eco-farm-security-resilience`](skills/eco-farm-security-resilience/SKILL.md)
- [`eco-farm-quality-gate`](skills/eco-farm-quality-gate/SKILL.md)

## Professional boundary

These skills are planning and coordination authorities. They do not replace legal survey, geotechnical design, structural design, hydraulic engineering, electrical protection design, veterinary care, environmental/public-health approvals, fire engineering, or food-safety compliance.
