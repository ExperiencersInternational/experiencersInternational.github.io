# Overclock your monitor

This guide is a work in progress, I should state that before we proceed.

You might have heard about overclocking your CPU or GPU, but have you ever overclocked your monitor? Today, this guide will tell you how to squeeze out every last Hz.

**WARNING: This can have unintended consequences, such as your display occassionally showing a weird image (like my Nitro 5 does at 75Hz). You should also check that your GPU and HDMI ports are capable at pushing out faster clock speeds. In some cases, such as overclocking my 4K TV with a GTX 1050, overclocking just makes the whole system crash, since the HDMI port can't do any more than 4K 60Hz.**

**NOTE: Depending on the device, you may also lose colour depth by overclocking, and you may see a blank screen when testing an overclock, this means you've set it too high.

## The guide

### Windows (NVIDIA)

This guide uses the NVIDIA Control Panel to overclock a display by setting a custom resolution. If you have Dynamic Super Resolution enabled, disable it before starting.

1. Open the NVIDIA Control Panel
2. Go to Display > Change Resolution
3. Select the display you want to overclock
4. Press 'Customise...'
5. Press 'Create Custom Resolution'
6. When looking at this menu, it may look complicated, but all you want to do is look at the refresh rate box, and increment by a reasonable increment, like 5Hz, press OK when done <br> ![image](https://user-images.githubusercontent.com/56035537/218334487-6737412d-2a15-4958-8022-3ef90b3f21c2.png)
7. Your display will now be tested to see whether it'll run at that refresh rate, if everything appears fine, click 'Yes' on this dialogue box, else, press 'No' <br> ![image](https://user-images.githubusercontent.com/56035537/218334574-129d6ce3-607e-42c8-a990-57fcfd5d2803.png)
8. Continue repeating from step 5 until your display doesn't produce an image no more, and go down by 1Hz each time once that happens

To apply the overclock, simply find the resolution you set the overclock on, and click the refresh rate that worked successfully.
