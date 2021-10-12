# ProtonAOSP

ProtonAOSP is a minimal custom Android ROM focused on UI/UX and performance, with a touch of security and privacy. It is based on [Android Open Source Project (AOSP)](https://source.android.com/).

## Getting source code

First, make sure you have an [Android build environment](https://source.android.com/setup/build/initializing) and the [repo tool](https://source.android.com/setup/build/downloading) set up. After that, run the following commands:

```
repo init -u https://github.com/ProtonAOSP/android_manifest -b sc
repo sync
```

This is a large download that will take approximately 100 GB of disk space, so plan accordingly.

## Building

You will need to create a device tree to build this ROM for your device. Below are some examples that have been customized to work well with ProtonAOSP:

- [Unified base tree for Pixel 5 and 4a 5G](https://github.com/ProtonAOSP/android_device_google_redbull)
- [Device-specific tree for Pixel 5](https://github.com/ProtonAOSP/android_device_google_redfin)
- [Device-specific tree for Pixel 4a 5G](https://github.com/ProtonAOSP/android_device_google_bramble)
- [Proprietary vendor blobs tree for Pixel 5 and 4a 5G](https://github.com/ProtonAOSP/android_vendor_google)

Good luck!
