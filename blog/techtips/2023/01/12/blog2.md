# HDMI video out through USB, why doesn't it work?
##### 12th January 2023

If you have a USB-C dock like me, you might notice that there's a HDMI port on it, but when you try to use it, it doesn't quite work. This article is a short explanation on why it doesn't work.

## The reason

Unfortunately, carrying a HDMI signal through USB-C (or rather DisplayPort, since I'm pretty sure that's the standard that it uses) is limited to USB-C 3.0 devices or newer. A lot of manufacturers like Xiaomi and Google do not have USB-C 3.0 support on their devices, likely as a cost saving measure, despite both manufacturers having a selection of high end phones (e.g. Google Pixel 7 Pro and Xiaomi 12 Ultra).

You might also know that this also happens with some devices like the Nintendo Switch despite them supporting USB 3.0 (I don't own a Switch Lite, but I'm pretty sure that runs on the 2.0 standard). The reason behind this is mainly because the Switch wants to require a power input (I'd recommend using the cable that comes with your device or a fast charger, since you may experience warnings with the power brick). A power input isn't required to output video, however due to how these manufacturers have configured their devices, it is needed.

## The solution for USB 2.0 or USB-A/B devices 

Yes, believe it or not, there is a solution to this. There's a chance you might have heard of a standard called DisplayLink and it actually allows you to carry a HDMI signal through an incompatible USB port (USB 3.0+ Type-C only ports are compatible with native video out, type A ports don't work, should have clarified this earlier). DisplayLink is supported on both desktop computers and Android devices (through the DisplayLink Presenter app).

---

Disclosure: I've never used DisplayLink before so I cannot confirm the support on certain devices.

---

Please share with your friends (thanks)

---
ExperiencersInternational © 2023
