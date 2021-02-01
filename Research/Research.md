
***

# Research

This is my research document for installing and maintaining Android, LineageOS, and other Android distributions through a virtual machine.

## LineageOS

### App compatibility

[[Android.stackexchange.com] does LineageOS allow us to install apps via Google play](https://android.stackexchange.com/questions/225938/does-lineageos-allow-us-to-install-apps-via-google-play)

**Notes to take away from this:**

* Google Apps (such as GMail, Google Play Store, Google Maps, etc) are proprietary and not included with an open source OS

* LineageOS has a package feature called **G**oogle **A**pps **P**ackages **(Gapps)** to run these apps on LineageOS. These **gapps** can range from basic apps to full-fledged suites

**Additional notes**

* Due to Google software being proprietary, you should be careful when installing it, as it can break the system, cause incompatibilities, and start tracking processes. In the future when you have enough memory, you should have a secondary virtual machine that rids of Google Apps and other proprietary software

## Android

### Installation

### Android x86 installation

**[Personal experience]** I originally never got the virtual machine to stay installed when I originally made Android x86 virtual machines. I would install it, but no matter what I did (snapshot, unmounting) upon restarting, the system would have to be re-installed. I eventually figured it out in 2020.

To solve this, make sure that during installation, you flag the option for auto installation, I don't remember what I did before, but this video helped me fix the issue [Warning: YouTube link](https://www.youtube.com/watch?v=137jBpJniNs)

### Android 2.3 (Gingerbread) 32 bit

#### Requirements

##### Video

Set the video memory to at least 16 megabytes

##### Memory

The system will need at least 64 megabytes of RAM. 128 or 256 megabytes is recommended

It is recommended to use at least 1 CPU core for the Virtual machine, I would use 2

Give the system at least 1 gigabyte of disk space (2, 4, 8, or 16 gigabytes is recommended)

##### Display

It is recommended to have touch screen support. Without touch screen support, the system is difficult to use, as the keyboard doesn't work on everything.

Without adjustments, your host computer should have a display of 1280x720 or higher to prevent scrolling, as the virtual machine will automatically load in 360x480/480x600 resolution

##### Other notes

This version of Android is very old. It is from December of 2010. The majority of modern Android apps will not work, you won't be able to install apps via the Android market, as it is too old, and the system should only be used for legacy purposes. Android apps that don't work on later versions of Android should be used here. You should install through an APK,

Recommended legacy apps: Jewels (MHGames) {works from: Android 1.5 (Cupcake) to Android 8.1 (Oreo)} other/unknown (recommend an app)

### Android 9.0 (Pie) 64 bit

#### Requirements

##### Video

Set video memory to at least 128 megabytes, and set the graphics controller to VBoxSVGA. VirtualBox labels this as "invalid settings" but it will still work.

##### Memory

The system will need at least 1024 megabytes of RAM. 2048 or 4096 Megabytes is recommended

It is recommended to use at least 2 CPU cores for the VM. 

Give the system at least 8 gigabytes of disk space (16, 32, 64 or 128 gigabytes is recommended)

##### Display

It is highly recommended to have touch screen support. Without touch screen support, the system is extremely difficult to use, and most apps won't work.

Without adjustments, your host computer should have a display of 2560x1440 or higher to prevent scrolling, as the virtual machine will automatically load in 1080x1920 resolution

***
