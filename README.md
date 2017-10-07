# How to upgrade Android for Samsung Galaxy S3 i9300
I decided to upgrade Android in my Samsung Galaxy S3 i9300 from version [4.3](https://www.android.com/versions/jelly-bean-4-3/) to a higher version which is not officially supported by Samsung. See also [Wiki](https://github.com/chovanj/Android/wiki) on this page.

## How to install an official Samsung firmware back to your mobile
1. [Download Odin flash tool](https://github.com/chovanj/Android/wiki/Odin-flash-tool).
2. [Download an official version of Samsung firmware](https://github.com/chovanj/Android/wiki/Official-version-of-Samsung-firmware-for-your-mobile).
3. [Enter download mode](https://github.com/chovanj/Android/wiki/Samsung-Galaxy-S3-i9300-Download-Mode).
4. Connect mobile and PC with a USB cable.
5. Unzip the downloaded firmware on your PC.
6. Run Odin and and you should see Added!! in Odin log.
7. Click on AP button in Odin and choose md5 file you have unzipped and wait until it's loaded. 
8. Click on Start button and whait until you see see PASS! in Odin.
9. Done!

### Troubleshooting

If loading takes too long you might be in so called LOOP, but don't panic. Just enter recovery mode. You can get to recovery mode the same way you get to download mode, but this time don't hold Volume Down, but Volume Up. From the menu choose wipe data/factory reset and confirm it. Then choose reboot system now and the issue should be resolved.

