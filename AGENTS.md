# Dataset repository

## Current annotation revision — 2026-11-17

DATASET.json and README describe 1.0.1-rc.1, a private immutable snapshot of
user-corrected annotations. Exact600 image hashes and bbox geometry/owners are
unchanged. Twenty-three annotation files changed, with2449 part shapes.
Technical checks pass600. On2026-11-17 the user reviewed and accepted the three
flagged Hair/Upper overlaps, attributing them to the downward camera view.
Record these as user-reviewed accepted geometry. Existing export voids cross-class
pixels, causing one reviewed Hair part to have zero eligible support. Keep this
evaluation-domain limitation explicit and distinguish user acceptance from full
visible-surface semantic verification. The private CURRENT.json
selects the audited manifest. The root private manifest.csv remains the1.0.0
baseline and its source annotation paths now contain user edits. Public1.0.0
records remain available at commit d77ad2e. Read the current README for counts
and review scope. User edits annotations. This revision audit changed no source
images, source annotations, ontology, scorer or frozen benchmark config.

This repository describes only the closed 600-image CCTV annotation dataset.
Keep the README dataset-focused and write Thai prose in a direct academic style.
The annotation specification and schema define the release contract.

Real images, annotations, per-image membership, camera/site metadata and provenance
remain in the external private data root. Commit only documentation, schemas,
synthetic examples, utilities, tests and reviewed aggregate statistics.

Preserve source image/annotation bytes and all recorded geometry and labels.
Use group_id as the current image-local owner. Keep legacy attributes intact.
Never treat unassigned pixels as verified background or infer absent parts.
No inference, training, new split or automatic annotation repair is implied.
Use existing compatible environments. Do not install packages or download weights
without authorization. Use fresh output directories and never overwrite a release.
