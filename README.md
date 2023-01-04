![VoidUI_Welcome_logo](https://user-images.githubusercontent.com/34755141/174216931-da41afc7-8436-4721-ade4-0dd0d4065c3a.png)

# VoidUI Tiramisu Project - Android 13.0


### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/VoidUI-Tiramisu/manifest -b aosp-13

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```