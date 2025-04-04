
HorizonDroid
===========

![HorizonBanner](https://github.com/HorizonDroidLabs/horizon/blob/main/horizon.svg)

Welcome to HorizonDroid!

HorizonDroid is based on AOSP and LineageOS, allows users to experience Google's latest Pixel updates while integrating useful features from known custom ROMs.
We currently support Android 15, with the latest security patches from Google.

### Quick Source Initialization ###

```bash
repo init -u https://github.com/HorizonDroidLabs/manifest.git -b fifteen --git-lfs
```

```bash
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune --retry-fetches=5 -j10
```

```bash
. build/envsetup.sh
```

```bash
lunch horizon_devicecodename-bp1a-buildtype
```

```bash
mka horizon
```

### Flag Sector ###

```bash
flag name maintainer
HORIZON_MAINTAINER := name
```
```bash
flag Gapps
WITH_GMS := false
WITH_GMS := true
```

[More build information](https://github.com/HorizonDroidLab/manifest)

### Important Links

- [Telegram channel](https://t.me/horizondroid)
- [Telegram group](https://t.me/HorizonDroidChat)

-----------------------------------------------------------------------------
![CreditsImg](https://github.com/HorizonDroidLabs/horizon/blob/main/credit.svg)
 Special thanks to All ROM Developers in this community
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**AxionAOSP**](https://github.com/AxionAOSP)
 * [**CrDroid**](https://github.com/crdroidandroid)
 * [**EvolutionX**](https://github.com/evolution-x)

-----------------------------------------------------------------------------
