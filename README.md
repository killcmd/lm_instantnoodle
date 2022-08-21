This is the Oneplus 8 Local Manifests

Inside of AOSP folder

```bash
mkdir arrow && cd arrow && repo init -u https://github.com/ArrowOS/android_manifest.git -b arrow-13.0 && mkdir .repo/local_manifests && wget -q -O .repo/local_manifests/roomservice.xml https://raw.githubusercontent.com/killcmd/lm_instantnoodle/arrow13/local_manifests/nissin_curry.xml && repo sync --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
