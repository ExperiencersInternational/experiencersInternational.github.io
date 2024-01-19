# Find your SIMs MMC and MNC information
##### 13th January 2023, last edited 19th January 2024

I recently ran into a situation where I wanted to check my MCC (mobile country code) and MNC (mobile network code) information, due to me being in confusion on whether my cellular service provider had me on O<sub>2</sub>, Vodafone or EE, since they technically hopped between 3 different networks with no notice last year. Today, I'm going to show you a quick tutorial on how to get this.

## Method 1 (Phone info / no additional software needed)

I desperately hope this isn't a MIUI only thing, don't see why it would since I did see the code being used for other smartphone manufacturers but if you input `*#*#4636#*#*` you should be greeted with a menu that says testing. Press phone information, and check which SIM you're checking for, press phone information 1 for SIM 1 and vice versa for any others. 

You then need to scroll down and find 'all mobile measurement info'. After that, you should see your MCC and MNC on your screen.

![Image of MCC and MNC number via Phone Info on Virgin Mobile](/assets/img/blog/techtips/2023/01/13/blog1/findmccandmncinfoimg1.jpg)

## Method 2 (SIM Cell Info from Play Store)

Download from [https://play.google.com/store/apps/details?id=ru.andr7e.simcellinfo](https://play.google.com/store/apps/details?id=ru.andr7e.simcellinfo).

Once installed, open and grant the phone permission (location is only required for the nearby cell towers feature).

Once done, your MCC+MNC should be displayed on screen.

![Image of MCC and MNC number via SIM Cell Info](/assets/img/blog/techtips/2023/01/13/blog1/findmccandmncinfoimg2.jpg)

## Check what provider your MCC+MNC code is for

If you'd like to find what provider your mobile country code and mobile network code is for, visit [mcc-mnc.net](https://mcc-mnc.net) and enter the two into the search box. For the UK specifically, 234 10 is O2 - UK, 234 15 is vodafone UK, 234 20 is 3 UK and 234 30 is EE.

---

Please, share with your friends if you found this useful

---

ExperiencersInternational © 2023
