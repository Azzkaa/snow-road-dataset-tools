# Snow road dataset preparation

Research snapshot, 26 November 2026. These are experimental scripts and selected evidence, not a production restoration system. Original project layout is preserved under `work/` and `outputs/`. Scripts depend on local model downloads, separate dataset manifests and historical directories; paths containing `/path/to/user-home` or `/path/to/external-media` must be configured. No clean reference is provided during deployment inference.

## Recorded scope and limitations
Tools for synthetic snow preparation, pair management, review and integrity checks. Dataset images and annotations are not redistributed.

## External models and data
Obtain upstream models and datasets separately under their original terms. No upstream weights, vendor repositories, environments, full datasets, credentials or optimizer checkpoints are included. See source imports and recorded provenance for exact dependencies. Third-party model licenses are not granted by this repository.

## Related repositories
- https://github.com/Azzkaa/road-inpainting-baselines
- https://github.com/Azzkaa/klein-road-restoration
- https://github.com/Azzkaa/road-lane-geometry
- https://github.com/Azzkaa/context-road-inpainting-hybrids

## Snapshot integrity
`PUBLICATION_MANIFEST.json` records the SHA-256 of included files. Source paths were anonymized in this public copy; originals remain unchanged. This snapshot does not establish complete reproduction on another machine.

## Full source snapshot
Download and extract [`source-snapshot.zip`](source-snapshot.zip) to retain the original directories. The archive contains all files listed in the publication manifest. Selected comparisons and entry scripts are also available directly in this repository. Local datasets and model files must be supplied separately.
