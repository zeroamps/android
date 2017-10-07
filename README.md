# How to upgrade Android for Samsung Galaxy S3 i9300
I decided to upgrade Android in my Samsung Galaxy S3 i9300 from version [4.3](https://www.android.com/versions/jelly-bean-4-3/) to a higher version which is not officially supported by Samsung. See also [Wiki](https://github.com/chovanj/Android/wiki) on this page.

## How to install an official Samsung firmware back to your mobile
1. Download [Odin flash tool](https://github.com/chovanj/Android/wiki/Odin-flash-tool).
2. [Download an official version of Samsung firmware](https://github.com/chovanj/Android/wiki/Official-version-of-Samsung-firmware-for-your-mobile).
3. Enter ![download mode](https://github.com/chovanj/Android/wiki/Samsung-Galaxy-S3-i9300-Download-Mode).
4. Connect mobile and PC with a USB cable.
5. Unzip firmware and then click on AP button in Odin. Choose md5 file you have unzipped and wait until it's loaded. Then click on Start button. When it's installed your mobile phone will be restarted and you should see PASS! in Odin.

### Troubleshooting

If loading takes too long you might be in so called LOOP, but don't panic. Just enter recovery mode. You can get to recovery mode the same way you get to download mode, but this time don't hold Volume Down, but Volume Up. From the menu choose wipe data/factory reset and confirm it. Then choose reboot system now and the issue should be resolved.

   ![Recovery mode](https://github.com/chovanj/Android/blob/master/android-system-recovery-3e.jpg)

