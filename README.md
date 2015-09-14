# sw5-012-baytrail-android-x86
Drivers and patch from my experiment in android-x86 kitkat for Acer Aspire Switch 10 SW5-012

*This repo is based on my acer switch 10 hardware, some model hardware mabe difference from this Eg. Wifi/Bluetooth

Some of My Hardware Specification
- Audio : Intel SST with Realtek I2S Codec rt-5640  (not work at this time)
- Wifi  : Realtek 8723BS (Bluetooth included) [SDIO Interface]
- Graphics : Intel Graphic HD (i915)
- Sensor : Inversense ????
- Camera : ???
- Touch : Synaptic INV7300
- CPU : Intel Atom 3735F SOC

# How to Build Android-x86
You can get Android-x86 Source at http://www.android-x86.org/getsourcecode
and apply my patch and driver before build.

# How to Test You Image?
1. After you build android image, you will get android-x86.iso and extract them to your usb flash drive.
2. On your Acer Tablet you need to disable secure boot and set boot priority to flash drive.
3. Turn off your tablet and plug in usb flash driver and turn on again
4. You will see grub screen and enjoy android-x86 in your acer aspire switch 10


# How to Install to my tablet permanently?
Install instruction coming soon
