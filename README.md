Android Open Source Andromeda Project
========

To initialize your local repository, use this command:

	repo init -u https://github.com/AOSAP/platform_manifest.git -b ten

 Then to sync up:

```bash
repo sync -f --force-sync --no-tag --no-clone-bundle -j$(nproc --all) --optimized-fetch --prune
```
