# system_asus_P027
Extracted System.img from Asus Zenpad 3S 10 / z500m - Model: P027

Asus Zenpad 3S 10 based on Mediatek MT8176 (upgraded MT8173) SoC.

For porting or general development. Based on Android 7.0, 2017-11-06 Security update.

If you are interested in porting a ROM for Xiaomi Mi Pad 3, then you've come to the right place!
I collected some devices that are based on the same SoC as our Mi Pad 3 (Codename: Cappu): Mediatek MT8176 / MT8173 (slightly different, but also okay for porting).
The following devices are similar to ours:

JDTab J01
Asus Zenpad 3S 10
Onda V10 Pro
Acer Chromebook R13
Alfawise Tab
Teclast T10
ALLDOCUBE Freer X9
Lenovo Flex 11
Lenovo N23 Yoga
Chuwi Hi9
Teclast Master T8
GPD XD+

Some of them have neither a firmware based on Android 7, nor a downloadable firmware anywhere. 
That's why i'm currently working on two ROM's, Asus Zenpad 3S 10 and GPD XD+. 
They are both based on Android 7.0, have the same kernel version-number and they contain both the latest libs for Vulkan API.

I uploaded for all three devices (1. Xiaomi Mi Pad, 2. Asus Zenpad 3S 10 and 3. GPD XD+) the extracted boot.img and system.img.

You can find them here:

Xiaomi Mi Pad 3
System: https://github.com/Goayandi/system_xiaomi_cappu
Boot:	https://github.com/Goayandi/boot_xiaomi_cappu

Asus Zenpad 3S 10
System:	https://github.com/Goayandi/system_asus_P027
Boot:	https://github.com/Goayandi/boot_asus_P027
Kernel:	https://github.com/Goayandi/android_kernel_asus_z500 (from the official Asus-Website, looks like Android 6)

GPD XD+
System:	https://github.com/Goayandi/system_GPD_gpd_en
Boot:	https://github.com/Goayandi/boot_GPD_gpd_en
