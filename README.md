## About

Wuthering Waves config for Android devices

For PC version check out Brandy's [WuWa Configs](https://github.com/AlteriaX/WuWa-Configs/)

## How to use

1. Copy `DeviceProfiles.ini` and `Engine.ini` to:
>  .../Android/data/com.kurogame.wutheringwaves.global/files/UE4Game/Client/Client/Saved/Config/Android/

**If don't want to use it** simply delete DeviceProfiles.ini and Engine.ini

### Config don't work

1. Open DevicesProfiles.ini with text editor of your choice
2. Add your device Model/GPU, if not sure add both:
    1. Find your device specifications at [GSMArena](https://www.gsmarena.com)
    2. Write your specs as in example for Poco X6 Pro bellow:
```
[Android_VeryHigh DeviceProfile]                                                ↰
some parameters                                                                 |
some more parametrs                                                             |
and maybe even more                                                             |
                                                                                |
[2311DRK48G DeviceProfile]                   <----- Model of Poco X6 Pro        |
BaseProfileName=Android_VeryHigh             <----- Name of graphics profile    ↲

[Android_Mali_G615-MC6 DeviceProfile]        <----- Dimensity 8300's GPU name, SoC from Poco X6 Pro
BaseProfileName=Android_VeryHigh

[Android_Mali_G615 DeviceProfile]            <----- Another possible name of D8300's GPU
BaseProfileName=Android_VeryHigh
```
