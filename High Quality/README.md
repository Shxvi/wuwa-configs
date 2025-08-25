## High Quality Config
**Balanced for high fidelity and playable FPS**

Recommended for Mid- and High-end devices with atleast 8G of RAM

### Differences in versions
-Adreno version has Adreno only optimisations and Frame Generation

-Mali verison cleaned from Adreno only params

## Features

* Vulkan API (Optional, In-game settings)
* Frame Generation (Adreno only, Optional, In-game settings)
* High Resolution
* More Reflections
* Better Water
* Normal Looking Folliage
* Find out more by yourself

## How to use
Download version for your GPU
* Adreno - Snapdragon SoC
* Mali - Mediatek SoC

Remove `-Adreno` \ `-Mali` from name

## How to change resolution

1. Open Engine.ini
2. Change this parameters as you want:
```
r.ScreenPercentage=100
r.SecondaryScreenPercentage.GameViewport=100

; numbers in percentage
; 100 = 100% = Native resolution (for example 1080p)
; 200 = 200% = Twice as native resolution (for example 1080*2 is 2160p, basically 4K)
; 75 = 75% = 75% from your native resolution (for example 75% of 1080 is 810p)
```

## TODO
1. HQ textures
2. Higher render distance
3. Better LODs
