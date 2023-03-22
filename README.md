![VoidUI_Welcome_logo](https://github.com/VoidUI-Tiramisu/manifest/assets/34755141/34db2823-4fe0-4d21-ae68-d144165aec26)

# VoidUI Tiramisu Project - Android 13.0 - QPR3 | Weekly / Daily Updates

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/VoidUI-Tiramisu/manifest -b aosp-13-weekly

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
