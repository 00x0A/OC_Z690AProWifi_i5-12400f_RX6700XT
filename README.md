# Hackintosh MSI Z690A Pro Wifi DDR4 RX6700XT i5-12400F

Specs:
- CPU: i5 12400F
- GPU: RX6700XT
- MEM: HyperX Fury Beast 2x16 (3600cl16)
- STORAGE: WD_BLACK SN850 1TB
- MOBO: MSI Z690-A Pro Wifi DDR4

Disclaimer: You do this at your own risk, I will not be held responsible for any issues during this process. If you have some issues open an issue and I will take a look at it.

Everything works out of the box, to set up wifi edit itlwm.kext > info.plist to use your specific wifi(s). If you want an interface for wifi selection you’ll need to download heliport.

Due to a recent bug in the NootRX driver you might want to disable sleep by running ```sudo pmset disablesleep 1 ```

Bluetooth might not work after first installing, after successfully installing you’ll need to run nvram reset to make it work.

Generate USBMap specific to your PC or use the premade one. Should some USB port not work you’ll need to map it yourself.

If you plan to dual boot Linux you’ll need appropriate drivers, dual booting Windows was tested and should work out of the box.

Lastly, GENERATE YOUR OWN SMBIOS, this is to make sure you’re not using anyone else’s SMBIOS or the default one which might get your Apple account terminated!