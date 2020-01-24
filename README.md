# Komodo OS (Android 10) #

![SourceForge](https://img.shields.io/sourceforge/dm/komodos-rom.svg?color=red&label=Komodo%20OS%20Downloads&style=popout-square&labelColor=121217&logo=openSUSE)

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/Komodo-OS-Rom/manifest -b ten

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch komodo_$device-userdebug

# Build the code
$ mka bacon -jX
```

---------------------------------------------------------------------------------------
 Credits:
 =======

 * [**LineageOS**](https://github.com/LineageOS)
 * [**AOSiP**](https://github.com/AOSiP)
 * [**PixelExperience**](https://github.com/PixelExperience)

---------------------------------------------------------------------------------------
