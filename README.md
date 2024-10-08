# hardware-wifi #

This module contains the STMicroelectronics libwifi HAL source code.

It is part of the STMicroelectronics delivery for Android.

## Description ##

This module version includes the first version of the libwifi Android abstraction layer.
Please see the Android delivery release notes for more details.

## Documentation ##

* The [release notes][] provide information on the release.
[release notes]: https://wiki.st.com/stm32mpu/wiki/STM32_MPU_OpenSTDroid_release_note_-_v5.1.0

## Dependencies ##

This module can't be used alone. It is part of the STMicroelectronics delivery for Android.
To be able to use it the device.mk must have the following packages:
```
PRODUCT_PACKAGES += \
    libwifi-hal-stm \
    android.hardware.wifi@<version>-service
```

## Containing ##

This directory contains the sources and associated Android makefile to generate the libwifi-hal library.

## License ##

This module is distributed under the Apache License, Version 2.0 found in the [LICENSE](./LICENSE) file.
