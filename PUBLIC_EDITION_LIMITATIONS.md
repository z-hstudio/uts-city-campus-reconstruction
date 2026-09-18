# Public Edition limitations

The current edition is an approximate, **PARTIAL** visual reconstruction of UTS City Campus (Ultimo, Haymarket and Blackfriars) with surrounding city context. It is not a completed survey-grade campus model. Grey surrounding masses are mostly context; neither campus ownership nor tenancy is inferred from presence in the scene.

Public v0.5.0 derives from accepted P069 (formal delivery P069_delivery). P070 and all unaccepted/failed candidates are excluded. Earlier releases are deliberately historical, not recommended current geometry.

## Differences from the private masters

Geometry, object transforms, topology and material assignments are preserved from each selected saved snapshot. Private operational custom properties and the old internal README text are removed and replaced by public attribution, licence, georeference and stable release metadata. Public overview camera and invisible metadata object are added. Unused material datablocks may be discarded by Blender on save; materials assigned to scene meshes are preserved and verified. Source properties needed for provenance are represented in separate data/notice files. Public previews use Blender Workbench material colours: reflections and transparent surfaces will differ from Cycles or a GLB viewer. No claim of pixel-identical rendering across engines is made.

REMOVED_FROM_PUBLIC_EDITION: private paths, operational metadata, private logs/conversations, reference image/PDF originals, intermediate reports, failed candidates, autosaves and recovery files. Most of these were workspace resources, not embedded Blender assets; no visual texture was removed because no image texture was present.

## Known approximation boundaries

- Flat z=0 ground proxy; no measured terrain or engineering grades.
- Many footprint heights are floor counts × an estimated height, not survey measurements.
- Landmark facades/roofs are recognizable approximations. Central crown, Tower entrances and CB08 curved brick/glass detail remain imperfect.
- Campus entrances, steps, ramps and over-street links are visual proxies, not verified accessible or safe routes.
- Trees and planting are grouped display proxies; species and individual placement are approximate.
- Blackfriars references include historical information; present-day occupancy is not certified.
- No interiors, complete structural systems, official branding package or construction accuracy is claimed.

The retained provenance audit has 1,808 object records: 1,094 with a populated `source` field and 714 older records without one. Missing source metadata is a provenance gap, not a finding that those records contain third-party binaries; future changes should improve or replace those records individually.

No known restricted third-party binary asset was found in the selected snapshots. No specialist legal opinion, school endorsement, or blanket clearance of underlying architecture and trademarks is claimed. Report a concrete rights concern through the repository; affected assets can be corrected or withdrawn without treating every independently authored asset as prohibited.
