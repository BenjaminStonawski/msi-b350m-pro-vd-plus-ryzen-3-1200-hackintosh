# OpenCore 0.9.8
## Specs
| **Component**    | **Model**                         |
| ---------------- | --------------------------------- |
| CPU              | AMD Ryzen 3 1200 @ 3.1GHz         |
| Motherboard      | MSI B350M PRO-VD PLUS             |
| RAM              | 16GB (2 x 8GB) G.Skill @ 2133MHz  |
| GPU              | GIGABYTE RX 5700 XT GAMING OC 8G  |
| Audio Chipset    | Realtek® ALC887 Codec             |
| Ethernet (LAN)   | Realtek® 8111H Gigabit LAN        |
| WiFi & Bluetooth | Fenvi T919 (BCM94360CD)           |
| OS Disk          | KINGSTON SV300S37A120G (SATA)     |
| Current OS       | macOS Ventura 13.6.5 (22G621)     |

## Things to know
I'm using Ventura because Broadcom cards have lost support in Sonoma and in order to get them working, you need to disable SIP and AMFI which is not a safe thing to do. But this EFI works with Sonoma as well.<br><br>
<b>With AMD CPUs, a lot of applications will crash or won't function properly, that's due to MKL, to fix this, head over to the 'mkl-fix' folder!</b><br><br>
If Handoff or Universal Clipboard don't work, check out my guide in the 'handoff-fix' folder!

## What works
✅ Ethernet + WiFi + Bluetooth => AirDrop, Handoff, iMessage/FaceTime <br>
✅ Graphics Acceleration (RX 5700 XT is natively supported)<br>
✅ AMD Power Management<br>
✅ All audio ports (front and rear speaker/mic ports, HDMI/DP audio) => Boot Chime<br>
✅ USB ports<br>

## Needs work
❌ Sleep is not perfect, PC can be put to sleep mode but won't load back

## Screenshots
![](https://media.discordapp.net/attachments/415562092138070018/1216536580202696754/Screenshot_2024-03-11_at_AM_12.35.11.png?ex=6600befa&is=65ee49fa&hm=92b0d28da5d740007b9d19d3778ab2d4aff1384a49383f8282010c8c2f924d34&=&format=webp&quality=lossless&width=1012&height=569)
