### Screen Capture
> Capture screenshots of your device's screen.

```bash
#capture screenshot
adb wait-for-usb-device shell screencap /sdcard screen.png

./adb exec-out screencap -p > $directory/Today_${lang_argument}_${i}.png 

# Capture a screenshot and save it to the device's SD card.
adb shell screencap -p /sdcard/screenshot.png 

# Pull screenshots
adb pull /sdcard/screen.png

# Delete screenhots?

```

There are far more options. You can even take a video.

—

### File Transfer
> Transfer files between your computer and your device.

```bash
#Push a file from your computer to your device.
adb push <local_file> <remote_path>
# Pull a file from your device to your computer.
adb pull <remote_path> <local_path>
```

—

Wearing the headset while connected to your laptop limits your ability to test the HMD.
Imagine you test Beat Saber, advanced hardcode level to get logs with proper performance data.
Even if you have a 3 meter cable it can get dangrous.

You connect the HMD via wifi.

### connect to device via wifi

1. you installed the RC or any other apk 

```bash
# Connect your Android device and adb host computer to a common Wi-Fi network.
adb devices
adb tcpip 5555

# to obtain the phone's IP address
adb shell ip addr show wlan0
# or
adb shell "ip addr show wlan0 | grep -e wlan0$ | cut -d\" \" -f 6 | cut -d/ -f 1" 
# copy IP address after the "inet" until the "/".

adb <ip-address-of-device>:5555
adb connect <ip-address-of-device>:5555

adb devices
# List of devices attached
device_ip_address:5555 device

# now view logcat output by running
adb logcat
```

=> note to self: double check this