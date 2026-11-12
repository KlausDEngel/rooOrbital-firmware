# rooOrbital firmware

Firmware updates for rooOrbital knobs.

You don't need to download anything here. A knob checks for a new version by itself, at most once a day, or when you choose **Settings → Check for Updates**. It installs the update only after you confirm.

The knob reads these two files from the [latest release](https://github.com/KlausDEngel/rooOrbital-firmware/releases/latest):

| File | Content |
|---|---|
| `firmware_version.txt` | the newest version, e.g. `1.03` |
| `rooOrbital_<version>.bin` | the firmware image |

Knobs with firmware from the rooExtend era need one USB flash to get the new memory layout. After that, they update from here.

Releases are made with `tools/make_release.sh` in the firmware's source repository. Please don't rename the files or add other files to a release.
