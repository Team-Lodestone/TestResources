# TestResources
Generic test resources for Lodestone.Tests

## General format
Test resources are split into `input` and `output` folders. The contents
of the `output` folder should never be uploaded. The `input` folder is further
categorized by the overall phase a resource is for.

Examples of this are: `preclassic`, `classic`, `indev`, `infdev`, `alpha`, `beta`, `release`.

Resources are further split by the game version and the asset type.
For example, a test world for Alpha 1.1.2_01 may be found in `alpha/a1.1.2_01/worlds/WORLD_NAME.zip`.

All test resources should be compressed before being uploaded either with `ZIP` or `DEFLATE` (GZIP).