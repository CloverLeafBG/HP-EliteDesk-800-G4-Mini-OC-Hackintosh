# HP-EliteDesk-800-G4-Mini-OC-Hackintosh


OpenCore based EFI for HP EliteDesk 800 G4 Mini 35W. EFI folder should also work with EliteDesk 800 G5 Mini, ProDesk 600 G4/G5 Mini and ProDesk 400 G4/G5 Mini.


![hp](https://user-images.githubusercontent.com/93620854/212490075-5390ef5f-fd90-4c76-ad38-4487d1f2bc08.png)





## Tested macOS Version

- macOS Catalina 10.15.7
- macOS BigSur 11.7.3
- macOS Monterey 12.6.3
- macOS Ventura 13.2


## System Configuration

- CPU:  Intel Core i5-8500T
- iGPU: Intel UHD Graphics 630
- RAM:  16GB DDR4 2667Mhz
- SSD:  Kingston A2000 500GB
- WiFi & Bluetooth: Intel 8265NGW
- Sound Card: Conexant CX20632
- LAN: Intel I219-LM

### BIOS Version

2.21.00 Rev.A


### Bootloader

OpenCore 0.8.8

### SMBIOS

Macmini8,1



## What's working

 - [x] Power Management
 
 - [x] iGPU Acceleration - hot pluggable display ports and DP->DVI adapters

 - [x] Sleep/Wake
 
 - [x] Audio (internal speaker, headphone jack and audio over DP)
 
 - [x] WiFi
 
 - [x] Bluetooth

 - [x] Ethernet

 - [x] USB 3.1 and USB-C (if present)
 


## What's not working

- [ ] DRM (no hackintosh solution for DRM with UHD 630 iGPU)


## Additional Notes

Don't forget to generate your own SMBIOS with https://github.com/corpnewt/GenSMBIOS. 

- ENJOY!

## Credits

Big thanks for the hardwork of deeveedee and all insanelymac community - https://www.insanelymac.com/forum/profile/1099364-deeveedee/
