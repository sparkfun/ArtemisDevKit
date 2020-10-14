SparkFun Artemis Development Kit
========================================

[![SparkFun Artemis Development Kit](https://cdn.sparkfun.com//assets/parts/1/5/7/4/6/16828-SparkFun_Artemis_Development_Kit-01.jpg)](https://www.sparkfun.com/products/16828)

* [*SparkFun Artemis Development Kit (DEV-16828)*](https://www.sparkfun.com/products/16828)
* [*SparkFun Artemis Development Kit with Camera (KIT-17071)*](https://www.sparkfun.com/products/17071)

The [*SparkFun Artemis Development Kit (DEV-16828)*](https://www.sparkfun.com/products/16828) is the latest board to be released around the SparkFun Artemis Module and it allows access to more software development features than previous Artemis based boards. Recommended software used to program the Artemis DK are the Arduino IDE, Arm® Mbed™ OS (Studio and CLI), and AmbiqSDK. An updated USB interface (MKL26Z128VFM4 Arm® Cortex®-M0+ MCU, from NXP) allows the Artemis Dev Kit to act as:

* Mass Storage Device (MSD): Used to provide drag and drop programming to the Artemis Module.
* Human Interface Device (HID): Used for the debugging interface to the Artemis Module.
* Communication Port (COM): Used to provide a serial communication UART between the Artemis and the USB connection (PC).


Repository Contents
-------------------

* **/Hardware**
   * Eagle design files (.brd, .sch)
   * Dimensions (.pdf and .png)
   * **/Production** - Production panel files (.brd)
* **/Reference**
   * Datasheets (.pdf)
   * Functional Block Digaram (.png)

Documentation
--------------
* [Hardware Getting Started Guide](https://learn.sparkfun.com/tutorials/1198) - Basic Hardware Guide for the Artemis DK
* Software Guides:
    * [Artemis Development with the Arduino IDE](https://learn.sparkfun.com/tutorials/artemis-development-with-the-arduino-ide) - A software guide for developing with the Artemis module (and related boards) in the Arduino IDE
    * [Artemis Development with Arm&reg; Mbed&trade; OS (Beta)](https://learn.sparkfun.com/tutorials/artemis-development-on-arm-mbed-os-beta) - A software pre-release guide to get started developing in with Mbed&trade; OS
    * Artemis Development with Arm&reg; Mbed&trade; OS (Pending release)
    * [Artemis Development with the AmbiqSDK](https://learn.sparkfun.com/tutorials/using-sparkfun-edge-board-with-ambiq-apollo3-sdk) - A software guide for utilizing the SparkFun Edge board with the AmbiqSDK
* [GitHub Repository for Apollo3 Board Support Packages (BSP)](https://github.com/sparkfun/SparkFun_Apollo3_AmbiqSuite_BSPs) - The Board Support Packages (BSPs) for SparkFun Apollo3 (Artemis) based boards to be used in the AmbiqSuite SDK
    * [ DAPLink Bootloader: `kl26z_artemis_dk_if.bin`](https://github.com/sparkfun/SparkFun_Apollo3_AmbiqSuite_BSPs/raw/master/artemis_dk/intfc/kl26z_bl.bin) - Underlying *bootloader* firmware for the MKL26Z MCU
    * [DAPLink Interface Firmware: `kl26z_bl.bin`](https://github.com/sparkfun/SparkFun_Apollo3_AmbiqSuite_BSPs/raw/master/artemis_dk/intfc/kl26z_artemis_dk_if.bin) - The accompanying *interface firmware* for the DAPLink debug probes from the MKL26Z to the target Artemis Module
* Development Software:
    * [SparkFun Ambiq Apollo3 Arduino Core](https://github.com/sparkfun/Arduino_Apollo3) - The SparkFun Arduino core for the Apollo3 MCU (i.e. the Artemis modules)
        * `.json` file needed for the SparkFun Ambiq Apollo3 Arduino Core:
        <br>
            <code><a href="https://raw.githubusercontent.com/sparkfun/Arduino_Apollo3/master/package_sparkfun_apollo3_index.json">https://raw.githubusercontent.com/sparkfun/Arduino_Apollo3/master/package_sparkfun_apollo3_index.json</a></code>
    * [Mbed™ OS](https://github.com/sparkfun/mbed-os-ambiq-apollo3) - Implementation of the Apollo3 (i.e. Artemis module) in Mbed&trade; OS
    * [AmbiqSDK](https://github.com/sparkfun/AmbiqSuiteSDK) - A copy of the AmbiqSuite SDK maintained by SparkFun
    * [pyOCD](https://github.com/sparkfun/pyOCD) - Implementation of the Apollo3 (i.e. Artemis module) for pyOCD
* Arduino Libraries:
    * [SparkFun LIS2DH12 Arduino Library](https://github.com/sparkfun/SparkFun_LIS2DH12_Arduino_Library) - The Arduino library for the accelerometer
    * [ArduinoBLE Library](https://github.com/arduino-libraries/ArduinoBLE) - The Arduino library for the BLE support

Product Versions
----------------
* [*SparkFun Artemis Development Kit with Camera (KIT-17071)*](https://www.sparkfun.com/products/17071) - v1.0 Initial Release *(kitted with Himax Camera)*
* [*SparkFun Artemis Development Kit (DEV-16828)*](https://www.sparkfun.com/products/16828) - v1.0 Initial Release

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
