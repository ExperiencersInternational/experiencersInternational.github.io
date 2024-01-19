# Make your own hard drive that can do anything
##### 16th January 2023

I don't have a spare USB stick or anything, so unfortunately I won't be writing from complete memory. Just thought I'd point that out before continuing with this guide.

In this guide, I'm showing some short and simple instructions on making a hard drive that can do quite a lot of things, and should be absolutely on your toolkit.

Any hard drive should work, but you should aim for at least 16GB for you to store everything.

## Step 1: Installing Ventoy onto your hard drive

**WARNING: This will clear your hard drive of any files on it, please back up before proceeding.**

Ventoy is an application that allows you to boot into your hard drive when turning on your computer to access various disk images.

The information should be fairly accurate, but I've never undergone it.

1. Download Ventoy from [https://github.com/ventoy/Ventoy/releases](https://github.com/ventoy/Ventoy/releases)
2. Save it to anywhere you want, as long as it's not the hard drive you're installing it to
3. Extract the ZIP to your desired location, as long as it's not on the hard drive you're installing it to
4. Open Ventoy2Disk as an administrator 
5. Select the drive to install it to and press Install
6. If you're asked to, agree to your hard drive being erased
7. Ventoy should hopefully be installed

To make use of Ventoy, you're going to need some ISOs, and I'd recommend getting an ISO of Windows 10 from Microsoft to get started. You may be greeted with an option to download the Media Creation Tool, you can use that if you want, and get an ISO from there, but the easier way would be changing your user agent to an OS other than Windows, since you'll be provided with an option to get the ISO without the tool. I'd also recommend getting a Linux Live CD, you'll have to choose which distribution best suits your needs.

Save your Windows ISO and any other ISOs to the root of the hard drive, and now, if your BIOS is configured correctly, you should boot into your hard disk when you next turn on your computer, and you'll be able to boot from your disk images.

## Step 2.1: Installing your portable apps swiss army knife

I ought to explain what a portable app is first. A portable app is essentially an app that can run from anywhere, and this can come in handy at times.

We're first going to install the PortableApps.com platform to the Ventoy disk you created, bearing in mind, you will need a Windows installation most of the time to run it.

1. Download the PortableApps.com platform from [https://portableapps.com/download](https://portableapps.com/download)
2. Run the EXE and install it to a PortableApps folder on your hard drive
3. PortableApps.com platform should now be installed

## Step 2.2: Installing essential portable apps

Most of the apps we're going to install are going to be from PortableApps.com, however we will install a few that's not offered on there.

1. Open the PortableApps.com Platform application that you installed onto your hard drive
2. Press Apps, and press Install New App, and after sort by title
3. You should then install Firefox (or K-Meleon, this is more compatible with older Windows versions), Kaspersky TDSSKiller, BleachBit, 7zip, HWinfo, HWmonitor, Rufus, and CrystalDiskInfo
4. Let these programs all install

I should probably provide a quick explanation for each app you just downloaded, so here it is:

- Firefox/K-Meleon: a web browser, Firefox has compatibility with Windows 7 or newer, and K-Meleon has compatibility with Windows XP (potentially older) or newer
- Kaspersky TDSSKiller: rootkit remover
- BleachBit: a better alternative to CCleaner that allows you to clean your systems junk and temporary files
- 7Zip: a powerful archive program, useful for extracting 7Z and RAR files
- HWinfo: displays information about your computer
- HWmonitor: monitors statistics such as CPU temperature
- Rufus: application that allows you to install a disk image to a USB
- CrystalDiskInfo: displays information about your hard disk and whether you need to replace it

For the other applications, we are relying on not using the platform, and we want to install a few essential apps.

### GUIFormat

Basically just the ability to format drives at FAT32 over 32GB.

1. Find where you installed PortableApps.com to and open the PortableApps folder
2. Make a folder with the name of GUIFormat
3. Download GUIFormat from [http://ridgecrop.co.uk/guiformat.exe](http://ridgecrop.co.uk/guiformat.exe) and save it in the folder you just created

### Nirsoft BlueScreenView

A useful tool providing extra information about a blue screen of depth.

1. Find where you installed PortableApps.com to and open the PortableApps folder
2. Make a folder with the name of BlueScreenView
3. Go to [https://www.nirsoft.net/utils/blue_screen_view.html](https://www.nirsoft.net/utils/blue_screen_view.html) and find download BlueScreenView in ZIP
4. Save the ZIP anywhere and open it
5. Once opened, select all of the files and paste it into the folder you created earlier

If your applications that you downloaded manually doesn't show up, restart the launcher, and if it still doesn't show up, check where you saved it.

## Conclusion

You've just learnt how to make a great USB toolkit for when you need it the most. Hopefully one day, this might just come to your rescue!

---

If this helped you, consider sharing with your friends, thank you!

---

ExperiencersInternational © 2023
