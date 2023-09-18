# Local manifests #
Local manifests for Redmi 6/6A (Certus)
# How to use this for building roms? #
### For Android 10 ###
```bash
# Grab local manifest and sync
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/hdrd13/local_manifests/main/ten.xml --create-dirs
repo sync -j$(nproc --all) --force-sync
```
### For Android 11 ###
```bash
# Grab local manifest and sync
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/hdrd13/local_manifests/main/eleven.xml --create-dirs
repo sync -j$(nproc --all) --force-sync
```
### For Android 12.1/12L ###
```bash
# Grab local manifest and sync
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/hdrd13/local_manifests/main/twelve_one.xml --create-dirs
repo sync -j$(nproc --all) --force-sync
```
