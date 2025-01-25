# Open-Core-EFI-for-Dell-Laptop-Broadwell-U
This EFI was made and tested specifically for the Dell Inspiron 5558. It is highly exclusive and difficult to find elsewhere because the Dortania Guide for building OpenCore EFI covers all Intel generations for desktops and laptops but does not fully address all Intel architectures, such as Broadwell-U.

If an EFI is built based on Broadwell instead of Broadwell-U, it will not boot, which proves there is a significant difference between the two architectures despite both being from the same generation (5th Gen Intel).

# 🗒 
This EFI includes specific modifications to on Dell laptops only. If you want to use it with non-Dell devices, you'll need to disable certain values in the config.plist. If you're unsure which values to disable, this website can help you: [[insert website link](https://sc.ocutils.me/)].

After more than 20 attempts, I finally figured out how to create a custom EFI for it. The idea was to copy some keys and values from a pre-made Clover config and then build the rest of the config based on Broadwell, as explained in the Dortania guide.

## System Information

| **Component** | **Model**                             |
| ------------- | ------------------------------------- |
| CPU           | Intel Core i3-5005u                    |
| Motherboard   | DELL OGGKVJ                           |
| RAM           | 4GB                                   |
| GPU           | Intel HD Graphics 5500                |
| Audio         | -     |
| Ethernet      | RTL8111                               |
| Wireless      | Intel® Wi-Fi 6 AX200                  |
| Storage       | Samsung 860 PRO SATA 2.5" SSD 1TB     |

# WORKING:
- [x] Power Management
- [x] Intel HD Graphics 5500
- [x] Sound **(Internal Speaker and Headphone working)**
- [x] Mic **(Internal and External both working)**
- [x] Wifi
- [x] Bluetooth
- [x] SD Card Reader
- [x] Ethernet
- [x] Adjust brightness 
- [x] USB 2.0 and 3.0
- [x] Trackpad **(All gestures supported)**
- [x] Sleep  **(working while power adapter is not connected and using battery)**
- [x] Battery Stat 
- [x] Tempareture Monitor 
- [x] Apple Store 
- [x] iCloud 
- [x] Fn feature **(Brightness and volume button works)**

# Not WORKING:
- [ ] iMassage **(Not working on my device. It might work on your device)**
- [ ] Facetime **(Not working on my device. It might work on your device)**

# Support Me
</div>
<a href='https://ko-fi.com/H2H1Q9W7J' target='_blank'><img height='48' style='border:0px;height:48px;' src='https://storage.ko-fi.com/cdn/kofi6.png?v=8' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
