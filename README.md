Getting started with Project Hexa
====================

Initialize Local Repository
-------------
```bash
  repo init -u https://github.com/Project-Hexa/manifest -b 13
```

Syncing Repository
-------------
```bash
  repo sync -c --force-sync --no-tags --no-clone-bundle -j$(nproc --all)
```

Lunch Command
-------------
```bash
  . build/envsetup.sh
  lunch hexa_<device_codename>-buildtype
  mka hexa
```