Getting started with NusantaraProject
====================

![NusantaraProject](https://github.com/NusantaraProject-ROM/Nusantara/blob/master/goodies/banner.png?raw=true)

Initialize Local Repository
-------------
```bash
  repo init -u https://github.com/predator112/android_manifest-1 -b 10
```

Syncing Repository
-------------
```bash
  repo sync -c --force-sync --no-tags --no-clone-bundle
```

Lunch Command
-------------
```bash
  . build/envsetup.sh
  lunch nad_<device_codename>-buildtype
  mka nad -j
```
