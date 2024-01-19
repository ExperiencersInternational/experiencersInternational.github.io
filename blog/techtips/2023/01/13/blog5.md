# Enable advertisement blocking on every device without installing any additional software
##### 13th January 2023, last edited 19th January 2024

Advertisements are annoying. I get that. And if you find them annoying, this guide will show you how to disable (well at least most of them), on every single device without needing something such as a PiHole. This uses AdGuards public DNS servers to run advertisement blocking.

Considering how I make YouTube videos and rely on the algorithm for revenue, I'd just like to say you will be harming people's revenue by doing this, and I'd recommend leaving a donation if you block adverts on their channel or site, besides, it'll often help more than the advertisement revenue.

**Warning: This can have unintended consequences such as some sites not loading with this, I'd recommend turning off your blocker temporarily if a certain site needs it.**

## The guide

### Generic

This guide can be followed on anything, from a 3DS (although there's a guide for that below) to your 3D television likely stuck in your basement. Yes I used 3D twice there. I cannot give exact information for your device, but you're going to have to deal with it.

1. Turn on your device and open your device's settings
2. Find network settings
3. Look for an option where you can configure your settings for the current network
4. If you see an option for DNS, set it to Manual instead of automatic, and enter these domains in the boxes which should now appear: `94.140.14.14` and `94.140.15.15`
5. Save your settings and most advertisements should be blocked

### Android 9+ (mobile devices, not TV)

May vary by different Android skins. For whatever reason, Android TV 9+ does not follow the same sort of instructions, blame Google.

1. Open settings
2. Search for 'Private DNS' (for Xiaomi devices, it's in Connection and Sharing)
3. Click on it and set to manual or private DNS provider hostname
4. Input `dns.adguard-dns.com`
5. Save and most ads will be blocked (YouTube will still show ads etc)

### Android TV and pre-Android 9 mobile devices

1. Open settings
2. Open network and internet
3. Select currently connected network
4. Press on IP settings
5. Press Static
6. Enter a local IP address (check your routers IP as well), e.g. 192.168.0.42 if your router is on 192.168.0.1 and there's nothing else occupying that space
7. Insert your gateway (usually 192.168.0.1)
8. Leave network prefix length as is
9. Set DNS 1 to `94.140.14.14`
10. Set DNS 2 to `94.140.15.15`
11. Advertisement blocking should now be configured (YouTube and certain streaming apps such as All 4 will show advertisements)

### Nintendo 3DS

The DSi follows a similar procedure to this, but you may have to scroll for internet settings and afaik, you need to use Connections 4, 5 or 6 to do this. By changing your DNS, if you use Sudomemo for Flipnote Studio, it will no longer work. This guide does not affect Nintendo DS Connections (Nintendo WFC in DS titles).

1. Turn on your 3DS and open System Settings
2. Press Internet Settings
3. Select Connection Settings
4. Select the connection you want to change your DNS for
5. Press change settings
6. Touch the right arrow and set auto-obtain DNS to No
7. Select detailed setup
8. Change the primary and secondary DNS to `094.140.014.014` and `094.140.015.015` respectively
9. Save settings and perform a connection test
10. Your advertisement blocker is now ready (although I don't know whether you're even going to see any adverts on a 3DS)

### Nintendo Switch

I feel like this should be fairly obvious, but if you have a modded Nintendo Switch, it's probably a wise idea not to change the DNS as it can lead to detection by Nintendo. Instead, you should use whatever DNS that stops Nintendo from detecting that you've been modded, albeit with the downside of having to see advertisements.

1. Turn on your console and open Settings
2. Scroll down on the menus until you find Internet, click on that when you do
3. Press Internet Settings
4. Choose the network you want to change your DNS for
5. Press Change Settings
6. Set DNS settings to manual
7. Set your primary DNS to `094.140.014.014` and your secondary DNS to `094.140.014.014`
8. Press Save
9. Perform a connection test if asked and it should work successfully
10. You're now blocking advertisements on your Switch (albeit YouTube will still show adverts etc, and I don't know how much of a use this is on Switch)

### LG TV (based on firmware 04.28.17 for a 3D TV from 2013)

Let's just say that the way to set up this is stupid. Really stupid. Thanks LG. Although then again, making a new network connection in most cases for the DSi is not a great thing either.

This guide is focused around having a wireless internet connection, so the steps for wired will be different.

Considering how this firmware is old, and likely significantly different from the latest line of TVs, this information may not be accurate.

1. Turn on your TV and open Home
2. Click on the Network icon
3. Press Start Connection
4. Press Other Network List
5. Press Manual Setup
6. Press Wired or Wireless depending on what you're using
7. (If you chose wireless) Select AP list (if your SSID is hidden, go to Enter the SSID instead)
8. (If you chose wireless) Select the network you want to set up advertisement blocking on
9. (If you chose wireless and network is not open) Input your password and press OK
10. Change DNS mode to manual input
11. Input `94.140.14.14` using the keypad on your remote, moving to the next box if it doesn't automatically move with the right D-PAD button and press OK
12. Your TV should connect successfully and advertisements will now be blocked

### Samsung Smart TV (based on version 2.91/2910)

Considering how Samsung's Smart TV UI looks dramatically different, this probably won't be accurate for modern TVs.

1. Turn on your TV and press Menu
2. Scroll down and press Network
3. Press Network Status
4. Press IP settings
5. Scroll down and select DNS setting to enter manually
6. Input `94.140.14.14` in DNS server
7. Press OK, your TV will check your network connection
8. Advertisements will now be blocked on your device

### Windows XP or newer (guide written for Windows 7 or newer)

Windows XP and Vista arranges their Control Panel in a different way, so they aren't mentioned here. It's also worth noticing that Windows 11 may not be compatible in the future, however there is already a replacement in Windows 11.

1. Press Windows key + R on your computer, it should open a Run box.
2. In this box, type 'control', this'll open the Control Panel application.
3. In Control Panel, if it's on the Category view, change to Large Icons.
4. Open up Network & Sharing Centre
5. Press 'Change adapter options'
6. Right click on the currently connected network adapter and press 'Properties'
7. Find 'Internet Protocol Version 4' and press 'Properties'
8. Press the button for use the following DNS addresses and put these in the two boxes: `94.140.14.14` and `94.140.15.15` and press OK
9. Repeat steps 7 and 8 if you want to do it for IPv6, but use the addresses in this additional information section
10. Press Close or OK, and you have now changed your DNS settings to block some advertisements!

## Additional information

You might have noticed for most devices that I used either the IPs `94.140.14.14` or `94.140.15.15` for the configuration or the secure DNS of `dns.adguard-dns.com`, but there are some others which can do blocking of inappropriate websites (it also enables safesearch as well).

Here's the additional ones:

- IPv6 Advertisement Blocking only addresses: `2a10:50c0::ad1:ff` and `2a10:50c0::ad2:ff`
- IPv4 Family Friendly DNS (as well as blocking ads): `94.140.14.15`, `94.140.15.16` and `family.adguard-dns.com`
- IPv6 Family Friendly DNS (as well as blocking ads): `2a10:50c0::bad1:ff` and `2a10:50c0::bad2:ff`

Also, when I get around to adding a Windows, Linux or macOS guide, you do not have to change your DNS to block advertisements, instead you can do something with your system files to block advertisements, you need to look for a 'hosts' list if you're planning to do that.

---

Please, share with your friends if this helped you! Thanks!

---

ExperiencersInternational © 2023
