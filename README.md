# How to set up and build
## Initialize repo
```$ repo init https://github.com/realme-pineapple-devs/kernel_manifest.git -b <branch> -m <manifest.xml> --depth=1 --no-tags```
## Sync
```$ repo sync --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j<number>```
## Build
```$ ./kernel_platform/oplus/build/oplus_build_kernel.sh pineapple gki```
