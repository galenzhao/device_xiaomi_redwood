Copyright (C) 2022 The LineageOS Project

Device configuration for Xiaomi Poco X5 Pro 5G
=========================================

The Xiaomi Poco X5 Pro 5G (codenamed _"redwood"_) is a mid-range smartphone from Xiaomi.

It was released in February 2023.

## Update

aosp: AP2A.240905.003.F1

packages: +BCR

## Build

kernel: 5.4.268-AtomX-e7d4c195d80b6c9b7e8240c6f8659109eaee777f

aosp: AP2A.240905.003.F1

firmware: V14.0.8.0.SMSEUXM

packages: GoogleCameraGo+OpenEUICC+BCR

https://github.com/galenzhao/device_xiaomi_redwood/tree/fourteen/prebuilt/app/GoogleCameraGo

https://gitea.angry.im/PeterCxy/OpenEUICC

https://github.com/galenzhao/vendor_bcr

## BCR

A known issue with BCR is that after all settings are completed, the first call cannot be logged. Therefore, please make a call from your Redwood to another phone first, and then subsequent calls can be recorded.

## PIF

Play Integrity: MEETS_BASIC_INTEGRITY, MEETS_DEVICE_INTEGRITY

Concerning Play Integrity, you have the option to build an APK incorporating your fingerprint data, such as `'https://github.com/galenzhao/packages_apps_Pif'`, or alternatively, you may join '[a group](https://t.me/+wbtKF0RQ9VY4YThl)' to locate a new prebuilt version.

## OTA supported

If you have already installed any version later than 14.0-20240711-1815, no action is needed. Otherwise, please first upgrade to PixelOS_redwood-14.0-20240711-1815.zip using ADB sideload; after that, OTA updates will work properly.

If you have manually installed any Updates.apk version prior to 14.0-20240711-1815, please uninstall it and use the version included in the 14.0-20240711-1815 ROM.

Alternatively, you can try the 'Updates.apk' version in the '14.0-20240722-1818' folder.

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Kryo 670, Up to 2.4 GHz, Octa-core CPU
Chipset | Qualcomm Snapdragon 778G 5G (SM7325-2-AB)
GPU     | Adreno 642L
Memory  | 6/8 GB, LPDDR4X
Storage | 128/256 GB, UFS 2.2
Shipped Android Version | 12
Battery | Non-removable 5000 mAh
Display | 2400 x 1080 pixels, 6.67 inches
Camera  | 108 MP main, 8 MP ultra-wide angle, 2 MP telemacro, 16 MP front

## Device picture

![Poco X5 Pro 5G](https://cdn1.coppel.com/images/catalog/mkp/7462/3000/74621343-1.jpg "Poco X5 Pro 5G")
