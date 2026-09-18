# Release asset rights audit — 18 September 2026

## Decision

The current UTS Community Edition remains publicly available under layered rights. No project-specific UTS, architect or other design-rights-holder authorisation for redistributing a 3D model is asserted. That absence is recorded as a boundary, not used as a blanket blocker for geometry independently authored from public or legally accessed references.

This audit uses the same source-based framework for Australian campus projects including UTS, USYD and UNSW. Other jurisdictions, including NTU Singapore, require a separate applicable-law and source assessment.

## Source classification

| Category | Observed material | Decision |
|---|---|---|
| `ORIGINAL_ZHSTUDIO` | Script-authored landmark and landscape additions, procedural materials, arrangement and documentation | Publish the author's own copyrightable contributions under Community License 1.0. Do not claim real-world building design, geographic facts or trademarks. |
| `PUBLIC_DATA_WITH_ATTRIBUTION` | OSM footprints, parts, routes, greens, trees and derived geographic mesh/data | Publish with ODbL 1.0 attribution and applicable share-alike/data-access obligations. The Community License noncommercial condition does not override ODbL rights. |
| `REFERENCE_ONLY` | UTS, architect, consultant, operator and government photos/diagrams/plans plus public street imagery | Use as visual reference only; originals are excluded from the public bundle and no licence to them is granted. |
| `REDISTRIBUTABLE_THIRD_PARTY` | Direct CAD/BIM/scan/point-cloud/model/texture package | None identified in the five selected snapshots; no such binary package is bundled. Any future direct asset needs evidence of redistribution permission. |
| `RESTRICTED_OR_UNCLEAR` | 714 retained provenance records have no `source` field value | Treat as a metadata gap requiring targeted provenance improvement, not as proof of a restricted third-party binary. If a concrete restricted source is found, withhold or replace that specific asset and record `REMOVED_FROM_PUBLIC_EDITION`. |

The machine-readable counts and overlapping source observations are in [SOURCE-CLASSIFICATION-2026-09-18.json](SOURCE-CLASSIFICATION-2026-09-18.json). The missing-source count is not an asset count: it includes old authored feature records, neutral context/massing records and other historical entries whose source field was never populated.

## Technical checks

Five source scenes were opened in isolated background Blender processes: P001, P005, P017, P024-r1 and P069/P069_delivery. Each had zero image datablocks, external libraries, external dependencies and object drivers. Model-generation scripts construct procedural meshes; detected import calls concern roundtrip validation of project-generated GLBs. The five selected public snapshots contain no direct third-party CAD/BIM, imported commercial model, scan, point cloud, DEM, raster texture, packed image, external font or linked Blender library.

The audit is evidence-based rather than a forensic guarantee about all historical creative activity. A hash proves the identity of a file, not authorship or a legal clearance of real-world architecture. The custom licence grants only rights the author can grant and does not grant school, architect, operator or trademark rights.

## Publication boundary

Reference images and drawings remain outside the repository and Release assets. OSM source and derived spatial data are separately distributed with `ODbL-1.0` and `© OpenStreetMap contributors` notices; the standalone [OSM-DATA-NOTICE.md](../../OSM-DATA-NOTICE.md) records the same boundary. The five historical Releases remain available because this review did not identify a concrete prohibited third-party asset. A precise asset-level report can trigger a targeted correction or withdrawal without treating every independently authored Australian campus asset as prohibited.
