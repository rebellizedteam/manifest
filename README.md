![RebellionOS](https://github.com/betallionos/manifest/raw/pie/logo.png)

# RebellionOS    [![Download RebellionOS](https://img.shields.io/sourceforge/dt/rebellionos.svg)](https://sourceforge.net/projects/rebellionos/files/latest/download)

### Sync ###


#### Initialize local repository
```
repo init -u https://github.com/RebellionOS/manifest -b pie
```

#### Sync
```
repo sync -c -f --force-sync --no-clone -jx
```

### Build ###

#### Set up environment
```
$ . build/envsetup.sh
```

#### Choose a target
```
$ lunch rebellion_$device-userdebug
```

#### Build the code
```
$ mka carthage -jX
```

### Credits ###

- PixelExperience (AOSP Base Done by @jhenique and team)
- Evolution X (Customization Base Done by Evolution X)
- LegionOS
- RevengeOS
- COSP
- LineageOS
- AICP
- AOKP
- BootleggersROM
- AospExtended
- GZOSP
- AOSZP
- Havoc OS
- Arrow OS
- AOSCP
- DescendantOS
- MSM-Xtended
- NitogenOS
- CarbonROM
- ValidusOS
