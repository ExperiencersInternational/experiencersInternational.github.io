# Restrict settings in Windows 10 and 11

This guide tells you how to restrict settings on Windows 10 and 11 using the Group Policy editor, or an app called PolicyPlus. This can be useful for locking down settings for a child for instance (say you could stop them accessing the settings for where you can download apps from).

**WARNING: Despite disabling/enabling some settings work how they should, it might not work for other settings. e.g. Disabling windowsinsider seems to remove the Windows Update page entirely. Proceed at your own risk, and take notes of what you're doing.**

**WARNING 2: This does NOT disable settings in the legacy Control Panel app, but if you want to do some digging, you can disable those as well.**

## Using PolicyPlus

1. To start, download PolicyPlus from [https://github.com/Fleex255/PolicyPlus/releases](https://github.com/Fleex255/PolicyPlus/releases). Save it to anywhere you want (even an external hard drive), this application operates portably.
2. After you've downloaded it, run it. If it asks you to get the latest ADMX definitions, press yes.
3. Press the Control Panel option in the sidebar (and make sure it says User or Computer above it). <br> ![image](https://user-images.githubusercontent.com/56035537/214152962-5a54ab2e-15c1-49b8-a5d7-ec4080d223d7.png)
4. If you look at the panel on the right, you should see an option called Settings Page Visibility, double click it. <br> ![image](https://user-images.githubusercontent.com/56035537/214153130-77624202-7f8c-4c06-9eaa-19832084197e.png)
5. In the dropdown box, if you're editing for all users, click Computer, otherwise, press User if you're editing it for the currently signed on user. If you have both settings for Computer and User, I believe User overrides it. <br> ![image](https://user-images.githubusercontent.com/56035537/214153368-3f3ee6b0-9153-4080-a652-b561558412f8.png)
6. Change Not Configured to Enabled. <br> ![image](https://user-images.githubusercontent.com/56035537/214153528-80692771-036a-4981-a7c4-b0876929771c.png)
7. A editable box should appear below it, and you should type `showonly:` if you only want specific settings to show, or `hide:` if you only want to hide specific settings. <br> ![image](https://user-images.githubusercontent.com/56035537/214156152-ed94f6c0-932e-41cb-912c-181cb67cb2b6.png)
8. Open [https://go.microsoft.com/fwlink/?linkid=2102995](https://go.microsoft.com/fwlink/?linkid=2102995) in a web browser and decide which settings applets you'd like to disable or enable. Make a list of them if you can.
9. After you've decided what you want to disable or enable, start typing them out in the text box, excluding the `ms-settings:` part, and using a semi-colon to separate each setting you want to disable or enable. <br> ![image](https://user-images.githubusercontent.com/56035537/214155992-42b70b00-5f31-4f98-85d6-7d88fe2c25ee.png)
10. Click Apply then OK after adding everything you wanted to.
11. Press File at the top and press Save Policies. <br> ![image](https://user-images.githubusercontent.com/56035537/214155263-852f6e9d-fbbd-4ca3-959c-74aafc28c6ac.png)
12. You should receive a message saying Success. Your settings have successfully applied. <br> ![image](https://user-images.githubusercontent.com/56035537/214155382-12e1d168-5fef-416a-8d0e-5f4fd63840c5.png)
13. Open Settings and your changes should have applied. If you think something is missing or not working, then you might have to enable more related components. <br> ![image](https://user-images.githubusercontent.com/56035537/214156384-923e999e-1d99-4e16-8d0b-18176f1add21.png) <br> ![image](https://user-images.githubusercontent.com/56035537/214156460-ee2a211d-690e-45cc-8cf4-28b61d2656f2.png)

## Using Group Policy Editor

Requirements: Windows 10 or 11 Pro edition or better, Home edition does not work with this method.

Just as a fair warning, I don't have a computer running Windows Pro edition, so it's just going from as far as I know.

1. Press Windows key + R and type `gpedit.msc`.
2. A windows should open with Group Policy Editor.
3. Go to Computer or User settings, depending on what your changing it for and find Control Panel.
4. Steps 4 to 10 should apply here from the PolicyPlus guide, then Step 13.

## Conclusion

You've now disabled specific settings on your device from showing up in the settings panel.

---

Share with a friend if this managed to help you. Thank you!

---

ExperiencersInternational © 2023
