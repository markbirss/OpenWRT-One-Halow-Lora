# OpenWRT-One-Halow-Lora
Meshtastic and Halow running on OpenWRT One

Halow via USB

Made my own since it was not sold seperately yet

<img width="3736" height="1017" alt="20260914_113201" src="https://github.com/user-attachments/assets/c1608303-ae03-465d-8f49-8da32661acaa" />

Now Available Seperately

3rd Party

https://www.alibaba.com/product-detail/WFDG8108-WiFi-HaLow-Dongle-Plug-And_1601962754478.html

SX1262/LR1121 via mikroBUS socket /dev/spidev2.0

<img width="985" height="609" alt="image" src="https://github.com/user-attachments/assets/9e7e0f50-0e9a-445a-9095-048226a69930" />

<img width="1719" height="1381" alt="image" src="https://github.com/user-attachments/assets/20d1cdec-1cba-4ff8-b748-8bb8e944cc70" />

<img width="1013" height="761" alt="image" src="https://github.com/user-attachments/assets/99a7a851-b549-4371-80af-86fe6309bbbd" />


```
Halow_support_for_OpenWRT_One.txt:fw_setenv boot_production 'led white on ; run ubi_read_production && bootm $loadaddr#$bootconf#mt7981b-openwrt-one-mikrobus-spidev ; led white off'

```

Tested also my HALOWSTICK under windows

<img width="1707" height="1060" alt="image" src="https://github.com/user-attachments/assets/843a9dbb-e543-439e-939d-43ebd43b1bd1" />

## ⚠️ Disclaimer
> **Warning:** Use of the firmware provided is entirely at your own risk. The project developer accept no liability for hardware damage, malfunctions, or safety hazards resulting from replication.

---

## Related Work

https://github.com/markbirss/dell-wyze-3040-lora-halow

## ☕ Support My Work
If this open hardware project brings utility to you, consider supporting my design pipeline!

[![Buy Me A Coffee](https://img.shields.io/badge/buy_me_a_coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/mark.birss)
