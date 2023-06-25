---
title: Lazy Overclocking & Undervolting RTX 3060 LP
date: 2022-02-04 21:22:10
categories:
- ['Overclocking']
feature: false
tags:
- 'NVIDIA'
- 'GA106-B'
---

# Prologue

After the Lenovo Tech came to my home and replaced my heatsink, I'm able to mess around with higher TDP on my 3060 again.

# My 3060

I don't really know how good my 3060 is binned, but it seems pretty decent to me.

![GPU-Z](image-20220204212659248.png)

## Micron VRAM

I don't mine, thus in my daily usage(casual gaming with AAA title like Tomb Raider and GTA and E-Sports titles like LOL and CSGO), I don't really feel a difference comparing to my old mobo that has Samsung VRAM. However, Micron failed even with mild OC due to hot temps. Hence I have to stick with +400 on M.CLK.

# OC Procedure

### Open up curve editor

I'm a lazy guy and I don't like gay lines. Therefore, I just open up MSI AfterBurner and jump right in onto the curve editor. 

![Stock Curve](image-20220204213505546.png)

### Drag the whole curve

It is a lazy method because of how simple it is to be achieving what I wanted: 

![After OC&UV](image-20220205080809360.png)

Basically I just drag the point at .85V up to 1830-1850 ish, then Re-select and drag the points right to 1V to the bottom. And here we are, the OC&UV is done!

### VRAM OC

Simply adding 400 on the M.CLK is more than enough.

|      | VRAM OC(Micron) | Result   |
| ---- | --------------- | -------- |
| 1    | 400             | &#9989;  |
| 2    | 800             | &#10062; |
| 3    | 1200            | &#10062; |

Micron VRAM runs really hot thus anything higher than or equal to 800 gives a `CLOCK_WATCHDOG_TIMEOUT`. (Yeah, it's hilarious how GPU OC causes a CPU often related BSOD)

# Result

![r/LenovoLegion - Legion7i 11800H 3060 max OC](Timespy.png)

# Conclusion

By default, the 3060 LP could only get to 8512 on Timespy, with this no-brainer +189 on C.CLK and +400 on M.CLK, a 10% increase in performance is clearly noticeable.
