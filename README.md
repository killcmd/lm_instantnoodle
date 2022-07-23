This is the Oneplus 8 Local Manifests

Inside of AOSP folder

```bash
mkdir aosp && cd aosp && repo init -u https://github.com/AOSPExtended/manifest.git -b 12.1.x && mkdir .repo/local_manifests && wget -q -O .repo/local_manifests/roomservice.xml https://raw.githubusercontent.com/killcmd/lm_instantnoodle/aex/local_manifests/nissin_curry.xml && repo sync --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
