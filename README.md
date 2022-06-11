This is the Oneplus 8 Local Manifests

Inside of AOSP folder

```bash
mkdir spark && cd spark && repo init -u https://github.com/killcmd/spark-manifest -b spark && mkdir .repo/local_manifests && wget -q -O .repo/local_manifests/roomservice.xml https://raw.githubusercontent.com/killcmd/lm_instantnoodle/SparkOS-12.3/local_manifests/nissin_curry.xml && repo sync --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
