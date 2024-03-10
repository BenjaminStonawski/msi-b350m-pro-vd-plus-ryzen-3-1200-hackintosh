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
I'm using Ventura because Broadcom cards have lost support in Sonoma and in order to get them working, you need to disable SIP and AMFI which is not a safe thing to do. But this EFI works with Sonoma as well.
