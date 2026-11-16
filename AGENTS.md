# Dataset repository

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
