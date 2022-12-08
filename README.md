This is the Oneplus 8 Local Manifests

Inside of AOSP folder

```bash
mkdir derp && cd derp && mkdir .ccache && repo init -u https://github.com/killcmd/derp-manifest.git -b 13 && mkdir .repo/local_manifests && wget -q -O .repo/local_manifests/roomservice.xml https://raw.githubusercontent.com/killcmd/lm_instantnoodle/derp13/local_manifests/nissin_curry.xml && repo sync --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
```bash
repo sync --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
```bash
export ccache_dir=~/derp/.cache && bash build/env* && lunch derp_instantnoodle-userdebug && mka derp -j$(nproc --all)
```
