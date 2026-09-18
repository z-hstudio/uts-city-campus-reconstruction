# UTS 公开发布完成报告

本报告记录本次真实 GitHub 发布及下载验证结果，不表示校园建模已全部完成。

## 1. Campus project

University of Technology Sydney（UTS），City Campus，Ultimo / Haymarket / Blackfriars 及周边城市背景。当前模型为近似视觉重建，仍有 PARTIAL 区域。

Creator: Manyousang Z / 漫游桑 Z  
Author: Ziheng Huang / 黄子恒  
Brand: z-hstudio

## 2. GitHub Repository

[https://github.com/z-hstudio/uts-city-campus-reconstruction](https://github.com/z-hstudio/uts-city-campus-reconstruction) — Public，默认分支 main。GitHub 仓库创建时间：2026-09-18T08:55:07Z。

## 3. Current Community Edition

[v0.5.0 — Public Community Edition](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/tag/v0.5.0)，来自已接受 P069 / P069_delivery。实际发布时间：2026-09-18T08:57:59Z。

## 4–5. Major releases 与内部版本

| Release / tag | 内部版本 | 首次公开时间 UTC | Release UUID |
|---|---|---|---|
| [v0.1.0](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/tag/v0.1.0) | P001 | 2026-09-18T08:56:55Z | `e366c432-b5c1-52bb-8e62-2f4bb3d22cec` |
| [v0.2.0](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/tag/v0.2.0) | P005 | 2026-09-18T08:57:07Z | `cdfa5d00-3304-5bcd-886c-7981b28e4df3` |
| [v0.3.0](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/tag/v0.3.0) | P017 | 2026-09-18T08:57:21Z | `1f3943db-ac64-5a09-8efc-363efe3f8c20` |
| [v0.4.0](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/tag/v0.4.0) | P024-r1 | 2026-09-18T08:57:37Z | `9c7da6bd-0f0c-51f3-b98e-94279ca110eb` |
| [v0.5.0](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/tag/v0.5.0) | P069 | 2026-09-18T08:57:59Z | `f9009de0-8055-59a3-bc6d-84308251c325` |

各阶段的主要变化、前后差异、当时局限和入选理由见 [HISTORY](../HISTORY.md) 及 [详细历史](history)。历史文件日期与本次公开时间分开记录，未伪造或回填 Git 历史。

## 6. 上传文件

每个 Release 15 个作者上传附件，共 75 个：`.blend`、`.glb`、`overview.png`、`core.png`、`osm-source-data.json.gz`、`osm-derived-spatial-data.json.gz`、`OSM-DATA-NOTICE.md`、`LICENSE.md`、`ATTRIBUTION.md`、`THIRD_PARTY_NOTICES.md`、`PUBLIC_EDITION_LIMITATIONS.md`、`RELEASE-NOTES.md`、`VALIDATION.json`、`RELEASE-MANIFEST.json`、`SHA256SUMS.txt`。

GitHub 还自动提供每个 tag 的源码 ZIP / tar.gz；其中是仓库文档与预览，不是额外模型版本。模型和地理数据压缩包均放在 Releases，未进入普通 Git 历史，未启用 LFS。

## 7. 排除的内容

私人母版、未接受 P070、失败 candidates、原始参考照片/PDF/图纸、私人日志和对话、账号凭据、缓存、自动保存和恢复文件均未上传。未发现需要打包的第三方 CAD/BIM/扫描/点云/贴图/DEM；五个场景的 image datablock、外部依赖和链接库均为零。其他校园未纳入仓库。

## 8. License

**z-hstudio Campus Model Community License，版本 1.0。** 定位 Source-Available Community Model，不是 OSI Open Source。许可只覆盖作者有权许可的原创贡献；地理事实和第三方权利不被据为己有。

## 9. 标准中文署名

```text
本作品基于漫游桑 Z（Manyousang Z）/ z-hstudio
制作的原始校园三维模型。
```

修改版：

```text
本作品基于漫游桑 Z（Manyousang Z）/ z-hstudio
制作的原始校园三维模型，并由 [名称] 进行修改。
```

## 10. 标准英文署名

```text
Based on the original 3D campus model by
Manyousang Z / z-hstudio.
```

修改版追加：`Modified by [Name].` 公开展示必须在 README、Credits、About、视频简介或其他合理可见位置提供署名，隐藏 metadata 不足以替代可见署名。

## 11. 商业许可

原创模型贡献的商业使用须事先取得单独书面许可；授权费、收入分成或两者结合另谈，无默认比例或买断。**Commercial permission does not waive attribution.** 本次未授权任何商业公司、建立商店或创建收费产品。依法独立获得的第三方数据权利不受额外商业审批约束。

## 12. Third-party notices

© OpenStreetMap contributors，ODbL 1.0。每个版本均附可独立获取的来源与派生空间数据。**这些数据及模型中对应的数据权利可按 ODbL 商用，不受原创艺术层的非商业条款限制。** 具体对象划分见 [MODEL-LAYERS.json](licensing/MODEL-LAYERS.json)。包含 OSM 衍生形态的 Central 等几何也明确列入映射数据层，不能笼统声称整个文件的一切几何均为独占原创。

照片、图纸和公开建筑资料仅作为建模参考；原件未分发。学校名称、建筑设计及商标权利归相应权利人。详见 [THIRD_PARTY_NOTICES](../THIRD_PARTY_NOTICES.md)、[SOURCES](../SOURCES.md) 和 [RIGHTS-AUDIT](licensing/RIGHTS-AUDIT.md)。

## 13. Public Edition 与 Private Master

五份私人母版 SHA-256 复核不变。公开副本保留网格几何、坐标、拓扑和实际使用的材质，替换内部运营元数据，加入作者、品牌、版本、仓库、稳定 UUID、地理基准和署名 Text。GLB 带 metadata extras。新增公开预览相机；Blender 保存可能清理未使用的材质数据块。

PNG 中自动写入的本机路径元数据已去除，像素压缩内容保持不变。预览采用 Workbench 材质颜色，不能据此宣称与 Cycles 或 GLB 查看器玻璃/反射效果完全相同。私人前台 Blender 未被后台发布流程覆盖。

## 14. 所有公开二进制 SHA-256

下表列出作者上传的所有模型、PNG 和 gzip 数据资产（30 项）。其余文字资产哈希及下载链接见 [publication-record.json](../manifests/publication-record.json)，每个 Release 的 SHA256SUMS 也包含 manifest 哈希。

| 版本 / 文件 | SHA-256 |
|---|---|
| [v0.1.0 / core.png](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.1.0/core.png) | `801fca845a95c8a8aecbfdb792d36784e3828fb4e2a5393784d3642c5e6e2974` |
| [v0.1.0 / osm-derived-spatial-data.json.gz](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.1.0/osm-derived-spatial-data.json.gz) | `5e79b1dcad10ec0898e315a4ee5649f86e4f5dd325f476ba4accf018e4b27a43` |
| [v0.1.0 / osm-source-data.json.gz](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.1.0/osm-source-data.json.gz) | `25f67122badb7de51f1fd1e1cabdb61353eeccc3b4ada70cabdfb02c16e1eefb` |
| [v0.1.0 / overview.png](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.1.0/overview.png) | `7ea5fd9361d0618178137f18623ee194eec2deb22d5c72519cab45558f5f1bbe` |
| [v0.1.0 / uts-city-campus-v0.1.0.blend](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.1.0/uts-city-campus-v0.1.0.blend) | `8e2a949a384742629cc177f579bceec36c4326695752eaec01bf006a3bb93d6f` |
| [v0.1.0 / uts-city-campus-v0.1.0.glb](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.1.0/uts-city-campus-v0.1.0.glb) | `a77a62d6f09cbe390e4194cf889de85067b05f2c5ee965e352fd6273ba9c5f51` |
| [v0.2.0 / core.png](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.2.0/core.png) | `d476b63d999b75faa0f8795b659d313d661353f33f770c215fd60b511eb74c75` |
| [v0.2.0 / osm-derived-spatial-data.json.gz](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.2.0/osm-derived-spatial-data.json.gz) | `2b3495cc456bfd75bfc5a0a57d668af01b4ba80cf05088d360d4a5d979032ac4` |
| [v0.2.0 / osm-source-data.json.gz](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.2.0/osm-source-data.json.gz) | `25f67122badb7de51f1fd1e1cabdb61353eeccc3b4ada70cabdfb02c16e1eefb` |
| [v0.2.0 / overview.png](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.2.0/overview.png) | `aca7c6acb37f161c11707ff3f0fdfcc329c4cfad78f283eeab00b603eeba6d0b` |
| [v0.2.0 / uts-city-campus-v0.2.0.blend](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.2.0/uts-city-campus-v0.2.0.blend) | `a20e465c8e13eacc281205571b620211870f668e80e7cf1e0afb56d40a9a82e8` |
| [v0.2.0 / uts-city-campus-v0.2.0.glb](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.2.0/uts-city-campus-v0.2.0.glb) | `747ab2b6c6bba19e42b5954d32ff9748f4c2d6db63ff3a60a0fd175b56b484ce` |
| [v0.3.0 / core.png](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.3.0/core.png) | `595e5afa1c18d0d59fd4f589ea9fc57b197fb46bc1213cf1de30fab660b90f5c` |
| [v0.3.0 / osm-derived-spatial-data.json.gz](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.3.0/osm-derived-spatial-data.json.gz) | `151932add59754a66cebfc66dd10abbdf8b2fd1971b149e7a22a5b907b25b2e5` |
| [v0.3.0 / osm-source-data.json.gz](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.3.0/osm-source-data.json.gz) | `25f67122badb7de51f1fd1e1cabdb61353eeccc3b4ada70cabdfb02c16e1eefb` |
| [v0.3.0 / overview.png](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.3.0/overview.png) | `01ee9368b111a0f76048a857a82b1c9d004a9602a23ac3cb89145de9e1a6de53` |
| [v0.3.0 / uts-city-campus-v0.3.0.blend](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.3.0/uts-city-campus-v0.3.0.blend) | `e573481419446d2f0fb8513a700d6a198597b6685a61827aa7f202df116ec392` |
| [v0.3.0 / uts-city-campus-v0.3.0.glb](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.3.0/uts-city-campus-v0.3.0.glb) | `47b9431377ae57a6084cb2b48099682059e8d48a46436babfcab3c9c02f4dc53` |
| [v0.4.0 / core.png](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.4.0/core.png) | `3ff4bdccf9bec8b2aa85a20c867d9cf29f125592202ae87bbb6cb9a9bd82378f` |
| [v0.4.0 / osm-derived-spatial-data.json.gz](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.4.0/osm-derived-spatial-data.json.gz) | `551930fafa41ab26f40786f3ca549d4ccebc0d6dd7a3112b79237ad1003734b6` |
| [v0.4.0 / osm-source-data.json.gz](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.4.0/osm-source-data.json.gz) | `25f67122badb7de51f1fd1e1cabdb61353eeccc3b4ada70cabdfb02c16e1eefb` |
| [v0.4.0 / overview.png](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.4.0/overview.png) | `7ec890b5108f8c877eb2d8f56637a6598fe6578d815cc2f2d7f3b6c1f56057f4` |
| [v0.4.0 / uts-city-campus-v0.4.0.blend](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.4.0/uts-city-campus-v0.4.0.blend) | `db1f24a00e45b3e73519b35868ca35d905a11d4769ab401620429ed97a50148b` |
| [v0.4.0 / uts-city-campus-v0.4.0.glb](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.4.0/uts-city-campus-v0.4.0.glb) | `3b2fdf48a3f53559a354c7d6fb9681ea52dbe7ecd90d11aea2e7be3fd523df32` |
| [v0.5.0 / core.png](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.5.0/core.png) | `5afabf7c477c2a5bd59433295f66881e20b82664465229b24b4a0d7f8d56d36c` |
| [v0.5.0 / osm-derived-spatial-data.json.gz](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.5.0/osm-derived-spatial-data.json.gz) | `4f1175f02b5d9ec5b5ef65536e384da3344546d689a106e031f85711005362da` |
| [v0.5.0 / osm-source-data.json.gz](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.5.0/osm-source-data.json.gz) | `25f67122badb7de51f1fd1e1cabdb61353eeccc3b4ada70cabdfb02c16e1eefb` |
| [v0.5.0 / overview.png](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.5.0/overview.png) | `2eae80aaf7b3b04d1d4145b6b6d8aed7409420117955775a81176f8e6f88e412` |
| [v0.5.0 / uts-city-campus-v0.5.0.blend](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.5.0/uts-city-campus-v0.5.0.blend) | `d31d556a439dc4cab6accffcaf2b8bffd541669f389fe5e240762472afb4e8f2` |
| [v0.5.0 / uts-city-campus-v0.5.0.glb](https://github.com/z-hstudio/uts-city-campus-reconstruction/releases/download/v0.5.0/uts-city-campus-v0.5.0.glb) | `ef048c23c64c5a330abf0308c173a7261e7ffb08d8b669de12ad7c520549b4a6` |

## 15. Git tags 与 commits

`v0.1.0`、`v0.2.0`、`v0.3.0`、`v0.4.0`、`v0.5.0` 均为实际已推送 annotated tags。为避免虚构历史，它们共同指向本次公开内容准备 commit `ced6599b38c8b9aae5d2e4dace830d17da028dc4`；历史差异由各 Release 的模型资产和 manifest 表达。之后的 main 提交补充 manifest 与真实发布验证记录，不改写 tags 或历史。

提交分为许可证/来源审计、历史/预览、manifest/哈希、实际发布验证记录四个有意义阶段。

## 16. 验证与隐私扫描

- 5/5 公开 Blender 文件重开通过；源几何指纹和实际使用材质保持一致。
- 5/5 GLB 独立回导通过；非零面积三角形数量与总表面积匹配，边界差值均为 0 米。导出器剔除的零面积三角形单列在各版本 VALIDATION 中。
- 已实际查看五个版本的核心区预览及当前全域预览；未声称所有渲染器像素一致。
- **75/75 GitHub 附件已真实下载，SHA-256 全部一致。** 校验了 Release manifest 和 SHA256SUMS；不是仅检查上传命令退出码。
- 11 个主要文档通过 GitHub API 回读与本地内容比对；公开仓库和当前 Release 页面已实际读取。
- 仓库与全部选定附件完成路径/凭据模式扫描、压缩数据解包检查、邮箱及文件类型检查，无命中。公开地理位置和公共建筑名称是有意发布的数据，不是私人住址。
- 采用明确文件清单上传，排除私有根目录和 `.blend1` 等恢复文件；正常 Git 中没有模型大文件。

扫描不能证明不存在任何未知混淆内容；结论仅限本次选择和实际检查的文件。

## 17. 尚未解决的权利与来源边界

没有宣称取得 UTS 或建筑设计方的专项三维模型分发授权，也没有独立律师审查结论。这不被设为所有自行建模资产的统一发布前置条件。本次按实际来源审计，未发现已包含而无权分发的具体第三方二进制资产；源照片/图纸均排除，OSM 依法单独标明。

底层建筑设计/商标权利、某些历史资料的当前时效以及各司法辖区具体法律适用，不能由作者自定义许可证或哈希证明解决。收到具体资产权利问题时，应针对该资产复核、移除或替换。**没有把“未发现受限资产”写成全面法律许可或官方认可。**

[统一校园发布审核框架](licensing/CAMPUS-PUBLICATION-AUDIT.md) 对澳大利亚 UTS / USYD / UNSW 使用同一标准；其他司法辖区单独评估。此文件不声称另外两个项目已经完成审计。
