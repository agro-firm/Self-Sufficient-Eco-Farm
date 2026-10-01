# Image and Blueprint Generation Standard

## Goal

Make future farm images, blueprints, diagrams, and renders visually consistent with the authoritative farm plan instead of allowing the image model to redesign the farm.

## Before generating any image

Read:
1. `docs/MASTER_PLAN_SUMMARY.md`
2. `docs/DECISIONS.md`
3. `docs/SPATIAL_DESIGN_STANDARD.md`
4. `docs/SPACE_REGISTRY.md`
5. the relevant individual space skill(s)

## Image classes

### A. Master top-view
Must show the whole 250 m × 220 m farm and preserve all authoritative zones.

### B. Dimensioned blueprint
Must show only approved dimensions. If a dimension is provisional, mark it `PROVISIONAL`.

### C. Single-zone architectural image
Must show one space only or one camera angle only, unless the user requests a composite.

### D. Engineering system image
Drainage, electrical, CCTV, road lighting, water, biogas, or security systems must use clear line types/legends and never imply an unapproved construction size.

### E. Photorealistic visualization
Must preserve topology and adjacency, but is not a measurement authority.

## Non-negotiable visual rules

- No separate central fish pond.
- The perimeter canal is continuous except engineered crossings.
- House/admin/playground/garage/pool is separated from dirty/service traffic.
- Large fodder bank remains the largest internal productive block.
- Tall orchard trees must not shade the open food-crop solar envelope.
- Livestock and poultry are on the service side with short manure routes.
- Processing/storage hub is compact and service-accessible.
- Biogas/wastewater stays away from the family/playground zone.
- Rooftop solar is preferred; do not cover prime crop fields with solar.
- Show two gates: main clean gate and service/emergency gate.
- Do not add fountains, decorative lakes, large lawns, or resort features unless explicitly approved.

## Text policy for images

- Photorealistic images: default to no text.
- Blueprint images: use short labels and dimensions only.
- Never rely on generated image text as authoritative documentation; dimensions must also exist in Markdown/CAD schedules.

## Camera rules

When asked for multiple angles:
- one image = one angle
- preserve the same master plan across all angles
- camera angle changes, farm layout does not
- identify camera direction in metadata/prompt

## Quality check

Reject/regenerate an image if:
- zones moved or disappeared
- canal becomes a pond
- roads cross the playground
- animals mix with clean food handling
- tall trees shade crop fields
- solar occupies prime crop land without approval
- dimensions conflict with the registry

## Residential pool visualization rule

A swimming pool is approved **only** inside the `04-house-admin-playground` residential/admin zone under D-013. It must never be depicted as a fish pond, irrigation pond, canal substitute, or decorative farm-wide water body. Images must keep a physical child-safety separation between pool and playground and must preserve the 2,200 m² parent boundary.
