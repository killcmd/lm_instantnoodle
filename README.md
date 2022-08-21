This is the Oneplus 8 Local Manifests

Inside of AOSP folder

```bash
mkdir derp && cd derp && repo init -u https://github.com/DerpFest-AOSP/manifest.git -b 13 && mkdir .repo/local_manifests && wget -q -O .repo/local_manifests/roomservice.xml https://raw.githubusercontent.com/killcmd/lm_instantnoodle/derp13/local_manifests/nissin_curry.xml && repo sync --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
