# Mi-A1-custom-rom
This is a guide to install custom rom for a friend ;)
I am not responsible if you start a nuclear war or kill animals by installing this rom
Start taking responsibility for your own sh$t

## Step 1
```
If (developer options not enabled)
{
  1. Go to settings -> system -> aboutphone
  2. Tap build number 7 times
  3. You will now see developer options under system
}
else
{
  1.Go to settings -> system -> developer options
}
```
## Step 2
In developer options
  1. Enable oem unlock
  2. Enable usb debugging
  
## Step 3
1. Download Minimal adb and fastboot from this [link](https://androidfilehost.com/?fid=746010030569952951) or from the resources folder
2. Install the downloaded exe, just click next leaving everything to default

## Step 4
1. Go to C:\Program Files (x86)\Minimal ADB and Fastboot
2. Double click cmd-here.exe
3. Connect your phone to computer via usb cable
4. In cmd  type > adb reboot bootloader 
5. Hit Enter
```
6. If (this is your first time)
{
  1. There will be a popup on your phone to allow usb debugging
  2. Tick always allow and tap OK
  3. Phone will reboot to bootloader screen showing FASTBOOT
}
else
{
  Phone will directly reboot to bootloader screen showing FASTBOOT
}
```

# Remove any lockscreen pin or passwords - Important !!!
# All the app data will be wiped during oem unlock - Can't help it

## Step 5
1. In the same cmd window type > fastboot oem unlock 
2. Hit Enter
```
if (bootloader already unlocked)
{
  1. It will display Device already unlocked -> OKAY -> FINISHED
}
else
{
  It will display OKAY -> FINISHED and the phone will restart
  2. Repeat ### Step 4
}
```

## Step 6
1. Download recovery-3.2.1-2-oreo.img from resources folder
2. Move the downloaded file to C:\Program Files (x86)\Minimal ADB and Fastboot
3. Make sure you are in FASTBOOT and connected to computer
4. In the same cmd window type > fastboot boot recovery-3.2.1-2-oreo.img
5. You will now see the TWRP recovery screen
6. Enter your PIN or password if it asks for it

## Step 7 
1. Download pixel experience from this [link](https://download.pixelexperience.org/changelog/tissot/PixelExperience_tissot-9.0-20190317-0420-OFFICIAL.zip/)
3. Download Twrp-recoveryInstaller-3.2.1-2-oreo.zip from resources folder
2. Copy the downloaded zips to your phone storage
3. In TWRP recovery Go to Wipe -> Advanced Wipe -> Tick Dalvik, System, Data 
4. Swipe to wipe and go to main recovery screen by tapping back
5. Go to Install -> Select PixelExperience -> Swipe to confirm Flash
6. Go and quickly take a pee
7. Tap back and select Twrp-recoveryInstaller-3.2.1-2-oreo -> Swipe to confirm Flash
8. Go to main TWRP screen -> Reboot -> Recovery
9. Reboot -> System


## Step 8 - optional !!! GPay stops working with root
1. Download magisk from resources folder
2. Copy to phone -> Install -> Reboot -> System ::: Why no detailed instructions ? (You are an expert now)

I guess it's enough for now.....open for changes
