# Fusion Physics Atlas Assets

Public, immutable browser-visualization derivatives used by FusionDigital.

This repository contains non-engineering glTF display meshes only. It does not publish source STEP/STP, B-Rep topology, PMI, authoritative dimensions, tolerances, manufacturing metadata, or control data.

The ITER educational visualization is a project-owner-authorized derivative for browser display and performance evaluation. It is not an authoritative ITER engineering model, is not suitable for manufacturing, CAE, metrology, physics validation, or safety decisions, and is not produced or endorsed by the ITER Organization.

Browser binaries are stored under bundle-specific directories with
content-addressed filenames. FusionDigital production pins an immutable full
Git commit SHA and fetches only exact files from `raw.githubusercontent.com`;
branches and tags are never runtime identities. A new revision uses a new
commit and new file digests rather than replacing an existing pinned object.

Published bundle directories:

- `iter-high-detail-v1/`: 18 reviewed ITER educational visualization shards.
- `exl50u-general-assembly-v1/`: 20 anonymous high-detail transport shards;
  no standard preview or runtime fallback is published. These files retain approximate
  metre-scale visualization geometry, but contain no source CAD file, PMI,
  dimension annotations, authoritative dimension table, BOM, material table or
  source assembly-tree labels and must not be used as engineering dimensions.

Scientific context for the separately generated analytic plasma proxy is documented in the main application repository and cites the IAEA/ITER Final Design Report and the Miller parameterization. No EFIT reconstruction or source equilibrium grid is distributed here.
