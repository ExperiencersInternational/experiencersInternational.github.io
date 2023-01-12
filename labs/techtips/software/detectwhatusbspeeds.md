# Detect the USB speeds of a device

Sometimes, we get lied to. In fact, I have a capture card that works great, it even captures DRM content (lol) but video is pretty buggy if I use the highest setting: 1080p60. If you know information about capture cards, you might know that USB 3.0 should be surely able to handle those speeds. But what if the device was lying? Unfortunately that was the case here, but today I'm going to show you a tool to check USB speeds.

## The software

As a warning, this software is only available for Windows, however it is supported from Windows 2000 (for 32-bit operating systems) or Windows XP (for 64-bit operating systems).

The program is called USBDeview and it contains a ton of information about any USB device connected to your computer, but what we want is the USB version information.

This app operates as a portable app, so it's fine storing it wherever you want (e.g. like an external hard drive).

## Instructions

1. To start, download it from [https://www.nirsoft.net/utils/usb_devices_view.html](https://www.nirsoft.net/utils/usb_devices_view.html). If your computer is running a 64-bit version of Windows, download the 64-bit version, otherwise, download the 32-bit version (if unsure of which one you have, press Windows key + X and then press System and it should list whether you're on a 64-bit or 32-bit OS).
2. When it asks what to do with the ZIP, press Open (this assumes you're using Microsoft Edge, if you're using Firefox, press Run, and if you're using neither, save to your downloads and open it).
3. Create a new folder to store the application in (e.g. C:\Users\User\Documents\Applications\USBDeview).
4. Extract the contents of the ZIP you downloaded to the folder you just created.
5. Plug the device you want to test in the fastest USB port in your computer (you might need to look at your device manual if you're unsure).
6. Run USBDeview as an administrator and press Accept at the UAC prompt (UAC only shows up Windows Vista or newer if you haven't changed UAC settings).
7. After running, locate your device in the list, for example in my case, I'm looking for a Macrovision USB Video device.
8. After locating, you'll need to scroll horizontally for a while until you see the column stating 'USB Version'.
9. You should now have the USB version of your device!

---

Please share with your friends (thanks)

---

ExperiencersInternational © 2023
