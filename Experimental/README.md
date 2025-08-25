## Experimental config
**All parameters maxed out**
**Not recommended to use on SoC lower than `Snapdragon 8 gen 1`/`Dimensity 8300` and bellow 8G of RAM**

Has many unused parameters related to PC

### Differences in versions
Original config works as-is only for Snapdragon devices
Both -Mali and -Adreno config cleaned from Lumen and Nanite crap
-Mali verison cleaned from Adreno only params, fixes texture glitches that appear only on Mali devices

### Special thanks to Mr.Otaku for Mali fixes

## Features

* Vulkan API (Optional, In-game settings)
* Frame Generation (Adreno only, Optional, In-game settings)
* High Resolution
* High Render Distance
* High Quality Textures
* High Quality Reflections (May not work on Mali)
* High Quality Water
* High Quality Folliage
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
1. Cleanup
2. Sort
3. Optimize
