# How to upgrade Android for Samsung Galaxy S3 i9300
I decided to upgrade Android in my Samsung Galaxy S3 i9300 from version [4.3](https://www.android.com/versions/jelly-bean-4-3/) to higher version which is not officially supported by Samsung. If you want to know more [go to Wiki](https://github.com/chovanj/Android/wiki) on this page.

## How to install an official Samsung firmware back to your mobile
If you want to install an official Samsung firmware back to your mobile follow this guide.

1. Download the latest version of [Odin flash tool](http://odin3download.com/). See [Wikipedia](https://en.wikipedia.org/wiki/Odin_(firmware_flashing_software)) if you want to know more about this tool.

2. Download an official version of Samsung firmware for your mobile. I used [Updato](http://updato.com/) webpage for downloading firmware. On the webpage you can search any firmware by device. For my Samsung Galaxy S3 i9300 I downloaded it from [ca3ffc731e7c11e6949e0cc47a44b7b2](http://updato.com/firmware-archive-select-model?record=CA3FFC731E7C11E6949E0CC47A44B7B2). I recommend backing it up because these sites are changing very quickly.

3. Enter download mode by following these steps below or watch this [video on YouTube](https://www.youtube.com/watch?v=WmdyFevTO3M).
    * Power off your Samsung phone, press and hold Volume Down, Home and Power keys at the same time.
    * Release all three buttons when Samsung phone reboot and you see a warning sign.
    * Press Volume Up to enter the main screen of download mode.
    ![Samsung download mode](https://github.com/chovanj/Android/blob/master/download-mode-samsung.jpg)

4. Unzip and run Odin flash tool. Then connect with a USB cable your mobile with your PC. If you do that for the first time you might have to wait a while because Windows has to install drivers for you mobile. After connecting you should see Added!! in log.

   ![Odin device added](https://github.com/chovanj/Android/blob/master/odin-device-added.png)

5. Unzip firmware and then click on AP button in Odin. Choose md5 file you have unzipped and wait until it's loaded. Then click on Start button. When it's installed your mobile phone will be restarted and you should see PASS! in Odin.
   
   ![Odin dowloading PASS!](https://github.com/chovanj/Android/blob/master/odin-firmware-pass.png)

### Troubleshooting

If loading takes too long you might be in so called LOOP, but don't panic. Just enter recovery mode. You can get to recovery mode the same way you get to download mode, but this time don't hold Volume Down, but Volume Up. From the menu choose wipe data/factory reset and confirm it. Then choose reboot system now and the issue should be resolved.

   ![Recovery mode](https://github.com/chovanj/Android/blob/master/android-system-recovery-3e.jpg)

