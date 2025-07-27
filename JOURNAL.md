---
title: Spin Amp
author: HoneyOak
description: USB-C DAC
created_at: 2025-07-25
---

~ [hack club highway](highway.hackclub.com)

#### Total time spent so far:

## 2025-07-24 Research (3 hours)
I found out that existing commmercial solutions are expensive, and there aren't many existing projects that implement a compact, budget DAC. There are plenty guides, though. I found a few from which I can get an idea of the BOM and feasability, as well as the rough circuit diagram.
This shouldn't be extremely difficult to pull off. Sure, I would have to maintain a clean circuit and prevent noise. But the circuit itself has 3 major components: USB to I2S, DAC, and OP-amp (and I'm adding a potentiometer for analog volume control).
Existing projects gave me lots of confidence though (some even handwired!): https://orronoco.blogspot.com/2022/01/build-your-own-portable-usb-dac.html, https://summivox.wordpress.com/2016/12/14/making-myself-a-usb-dac-headphone-amp-part-1/
That said, I have never made a 4-layer PCB before (or really, never made a pcb at all yet). So this would be a fun challenge! 

## 2025-07-25 Schematic (6.5 hours)
Done with the schematic today! Phew. That took a lot of research. Selecting the right modules, getting the right footprints, and scrolling through datasheet after datasheet to find the correct configuration. Finally, though, I think I'm done with possibly the hardest part of this build!

<img width="1439" height="1015" alt="image" src="https://github.com/user-attachments/assets/4ef94a13-1a13-4ebd-899c-c6cd69d44cfb" />

## 2025-07-26 PCB (2 hours)
Arranged the PCB Layout, placing caps and resistors in optimal positions. Using a 4 layer PCB would greatly reduce noise and electromagnetic interference, which is particulary important for a high quality audio device.

<img width="963" height="762" alt="image" src="https://github.com/user-attachments/assets/99641e1a-6297-4409-a402-8b6303b889ea" />


## 2025-07-26 More KiCAD (4.5 hours)
Done with PCB!!! took a while to have everything routed because I had to be very careful with what layer each trace needs to go to.
<img width="1020" height="872" alt="image" src="https://github.com/user-attachments/assets/43d9eb0a-e726-4bfc-b9c0-553a86384fb3" />
<img width="1332" height="957" alt="image" src="https://github.com/user-attachments/assets/2278206f-1d4d-4092-a20d-677f714a23a1" />

