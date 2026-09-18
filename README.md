# UTS City Campus Reconstruction

**Original campus reconstruction: Manyousang Z / z-hstudio**  
Creator: Manyousang Z / 漫游桑 Z · Author: Ziheng Huang / 黄子恒

A **Public Community Edition / Source-Available Community Model** of the **University of Technology Sydney City Campus**, covering Ultimo, Haymarket and Blackfriars with surrounding city context.

**[Download current v0.5.0](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/tag/v0.5.0)** · [All historical releases](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases) · [Licence](LICENSE.md) · [History](HISTORY.md)

- **Allowed:** personal learning, education, research, noncommercial display/video/web/game/VR/AR, editing, conversion and noncommercial derivatives under [Community License 1.0](LICENSE.md).
- **Required visible source credit:** “Based on the original 3D campus model by Manyousang Z / z-hstudio.” 中文：“本作品基于漫游桑 Z（Manyousang Z）/ z-hstudio 制作的原始校园三维模型。”
- **Modified work:** retain the source credit and add “Modified by [Name].” Renaming, remeshing or changing materials/formats does not erase the origin.
- **Commercial use of original creative contributions:** obtain a separate written licence; fee, revenue share or both are negotiated. **Commercial permission does not waive attribution.** [Commercial terms](COMMERCIAL-LICENSE.md).
- **Third-party data:** OSM and mapped derivative data retain **ODbL 1.0**, including commercial-use rights; the community noncommercial restriction does not apply to those data. Reference photos/drawings are not distributed. [Notices](THIRD_PARTY_NOTICES.md).
- **Approximate visualization, not survey data:** not construction, safety navigation, legal-boundary or precise digital-twin information. Current model remains **PARTIAL**.

This is an independent community reconstruction project. It is not affiliated with, endorsed by, or officially produced by the university. School names, logos and trademarks belong to their respective rights holders. No university or architect authorization is asserted. This custom noncommercial licence is **not OSI Open Source**.

![Current core campus preview](previews/current/core.png)

Based on the original 3D campus model by **Manyousang Z / z-hstudio**. © OpenStreetMap contributors, [ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/). Workbench preview; material/glass appearance varies by viewer.

## Download and use

Release assets include editable Blender `.blend`, interchange `.glb`, overview/core PNG previews, OSM source and derivative spatial databases (`.json.gz`), licence/attribution notices, `SHA256SUMS.txt` and `RELEASE-MANIFEST.json`. Model binaries live in **GitHub Releases**, not normal Git history or Git LFS. Download the notices with the model.

The scenes were saved and reopened in Blender 5.2.1 LTS. GLBs were imported into fresh Blender scenes and checked for finite coordinates, bounds and nonzero-area geometry. Procedural materials need no external image files. Verify downloaded files with `shasum -a 256 -c SHA256SUMS.txt` after downloading all files listed there. The checksum file omits itself to avoid circular hashes; the manifest lists payload hashes and does not hash itself.

The public `.blend` stores creator, author, brand, project, repository, licence, version, stable release UUID, attribution and georeference. Read its `Z_HSTUDIO_ATTRIBUTION` text block. GLB metadata is carried in an invisible `__ZHSTUDIO_METADATA__` node; public visible credit is still required.

## Historical releases

| Release | Internal snapshot | Phase |
|---|---|---|
| [v0.1.0](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/tag/v0.1.0) | P001 | Geographic foundation |
| [v0.2.0](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/tag/v0.2.0) | P005 | First landmark identities |
| [v0.3.0](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/tag/v0.3.0) | P017 | Broader building coverage |
| [v0.4.0](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/tag/v0.4.0) | P024-r1 | Precinct landscape and connections |
| [v0.5.0](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/tag/v0.5.0) | P069 / P069_delivery | Current Community Edition |

These are first public editions of actual historical snapshots, not backdated Git histories. [Detailed history](HISTORY.md) · [Provenance and evidence limits](RIGHTS_AND_PROVENANCE.md) · [Public/private differences and known gaps](PUBLIC_EDITION_LIMITATIONS.md).

## Project records

[Attribution templates](ATTRIBUTION.md) · [Sources](SOURCES.md) · [Rights audit](docs/licensing/RIGHTS-AUDIT.md) · [Consistent campus audit framework](docs/licensing/CAMPUS-PUBLICATION-AUDIT.md) · [Changelog](CHANGELOG.md) · [Contributing](CONTRIBUTING.md) · [Release manifests](manifests/releases)

Private masters, original reference images/PDFs, credentials, conversations, logs, caches, autosaves and unaccepted candidates are not published. Known rights issues can be reported with a precise asset/version and supporting source; this is not a blanket legal clearance of real-world architecture.
