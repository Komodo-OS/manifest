# Komodo OS #
<p align="center">
<a href="https://imgur.com/8RoBGQS"><img src="https://i.imgur.com/8RoBGQS.png" title="Banner"/></a>
<a href="https://sourceforge.net/p/komodos-rom/"><img src="https://img.shields.io/sourceforge/dm/komodos-rom.svg?color=red&label=Komodo%20OS%20Downloads&style=popout-square&labelColor=121217&logo=openSUSE"></a>
<a href="https://jenkins.komodo-os.my.id/job/komodo-release"><img src="https://jenkins.komodo-os.my.id/job/komodo-release/badge/icon?style=flat-square&subject=Build%20Jenkins"></a>
<a href="https://crowdin.com/project/komodo-os-rom"><img src="https://badges.crowdin.net/komodo-os-rom/localized.svg"></a>
<a href="https://t.me/KomodOSRom"><img src="https://img.shields.io/badge/Telegram-Chat-blue?style=popout-square"></a>
</p>

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/Komodo-OS/manifest -b 13

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
$ mka komodo -jX
```

### Developer ###

- [Become maintainer for your device](https://github.com/Komodo-OS/manifest/wiki/Maintainers-Requirements)

---------------------------------------------------------------------------------------
 Credits:
 =======

 * [**LineageOS**](https://github.com/LineageOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**Nusantara**](https://github.com/Nusantara-ROM)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**PixelOS**](https://github.com/PixelOS-AOSP)

---------------------------------------------------------------------------------------

