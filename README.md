# Komodo OS Rom #
<a href="https://imgur.com/8RoBGQS"><img src="https://i.imgur.com/8RoBGQS.png" title="Banner" height="200" width="450"/></a>

![SourceForge](https://img.shields.io/sourceforge/dm/komodos-rom.svg?color=red&label=Komodo%20OS%20Downloads&style=popout-square&labelColor=121217&logo=openSUSE)
[![Build Status](https://jenkins.komodo-os.my.id/job/komodo-release/badge/icon?style=flat-square&subject=Build%20Jenkins)](https://jenkins.komodo-os.my.id/job/komodo-release)
[![Crowdin](https://badges.crowdin.net/komodo-os-rom/localized.svg)](https://crowdin.com/project/komodo-os-rom)

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

### Developer ###

- [Become maintainer for your device](https://github.com/Komodo-OS-Rom/manifest/wiki/Maintainers-Requirements)

---------------------------------------------------------------------------------------
 Credits:
 =======

 * [**LineageOS**](https://github.com/LineageOS)
 * [**AOSiP**](https://github.com/AOSiP)
 * [**PixelExperience**](https://github.com/PixelExperience)

---------------------------------------------------------------------------------------
