# Allsky Camera for PI5 amended for SHT31 Temperature and humdidty sensor 

![image](https://github.com/user-attachments/assets/7c9247cb-81ff-4be3-af64-e61accaadfd1)

This is the source code and primary credit for SW:
 [on Instructables](http://www.instructables.com/id/Wireless-All-Sky-Camera/).


<!-- =============================================================================== --> 
## Requirements

In order to run the Allsky software you need:

 * A Raspberry Pi Zero 2, Pi 2, Pi 3, Pi 4, Pi 5, or Le Potato.
 * A version of the Raspberry Pi OS.  Other operating systems like Ubuntu are NOT supported.  If possible use the newest Bookworm 64-bit release of Pi OS with the "Desktop" version. Bullseye will also work. __Buster support will be dropped in the next major release__.
 * A camera:
    * Any ZWO camera sold before February 1, 2025,
    * or one of the following cameras:
       * Raspberry Pi:
          * HQ (IMX477 sensor)
          * Module 3 (IMX708 sensor)
          * Version 1 (OV5647 sensor; NOT RECOMMENDED: 0.9 second maximum exposure)
       * Arducam:
          * 16 MP (IMX519 sensor)
          * 64 MP (arducam_64mp sensor)
          * 462 (arducam-pivariety sensor)
          * 64 MP Owlsight (OV64a40 sensor)
       * Other:
          * Waveshare imx219-d160 (IMX290 sensor)
          * OneInchEye IMX283 (IMX283 sensor)
          * IMX290 60.00 fps
