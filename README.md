# Local manifests #
Local manifests for certus
# How to use this? #
### For building Android 10 ###
```bash
# Grab local manifest and sync
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/hdrd13/local_manifests/main/ten.xml --create-dirs
repo sync -j$(nproc --all) --force-sync
```
### Android 11 ###
```bash
# Grab local manifest and sync
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/hdrd13/local_manifests/main/eleven.xml --create-dirs
repo sync -j$(nproc --all) --force-sync
```
### Android 12.1 ###
```bash
# Grab local manifest and sync
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/hdrd13/local_manifests/main/twelve_one.xml --create-dirs
repo sync -j$(nproc --all) --force-sync
```
