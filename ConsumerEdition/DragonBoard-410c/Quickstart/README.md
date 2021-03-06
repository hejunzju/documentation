# Quickstart

Learn about your DragonBoard™ 410c board as well as how to prepare and set up for basic use

## Setup - What you will need

**Need**
- [Power adapter](PowerAdapter.md)
   - 96Boards specifications requires a 6.5V-18V with 2000mA Power adapter
- MicroSD card with adapter
   - For quick and easy switching between operating systems and extra storage
- USB Keyboard and Mouse
   - With two USB-A connectors, all 96Boards can be equiped with a full sized keyboard and mouse
- Full size HDMI Cable
   - All 96Boards are equiped with a full sized HDMI connector
- Monitor
   - HDMI capable monitor is recommended

**Optional**
- [Mezzanine Products](../../../MezzanineProducts/README.md)
   - These mezzanine add-ons will allow you to access a variety of peripherals on the DragonBoard™ 410c
- USB to MicroUSB cable
   - This is needed for serial console interface and fastboot/adb commands
- USB to ethernet adapter and ethernet cable
   - For connecting to a network without using WiFi

***

## Getting started with...

#### Android

**The DragonBoard 410c comes preloaded with Android and can be up and running with a few simple steps:**	

- Connect the DragonBoard 410 to your display with the HDMI cable. It is important to do this first because the monitor will not detect the board if it is connected after starting. Ensure that the source for the display is switched to the HDMI port you are using.
- Connect the USB keyboard and mouse. Do not connect the USB OTG port to your computer – this will prevent the keyboard and mouse from operating. The USB OTG port is the micro USB connector on the board.

![dipswitch](https://www.96boards.org/wp-content/uploads/2015/04/dip_blue_20150611_142555-300x205.jpg)

- Ensure switch S6 is set to the factory default (0-0-0-0, i.e. all switches are off – see picture on right).
- Switch S6 can be found on the reverse side of the board in the bottom right-hand corner.
- Verify the HDMI cable and USB cables are plugged in, then connect the power supply to the DragonBoard. The board will begin to boot Android immediately. Note that this may take a minute or two to get to the Android screen on the HDMI Monitor.
- At this point, you can setup WiFi in the Android settings and then begin to work with Android on the board.

Please refer to the DragonBoard 410c [Android User Guide](../../../dragonboard410c/AndroidUserGuide_DragonBoard.pdf) for further information on working with Android and some basic programming examples.	

#### Linux

There are several ways to run Linux on your DragonBoard 410c. Procedures to boot/install from a micro SD card as well as installing Linux using fastboot via the USB OTG port can be found [here](../Installation/README.md) and in the basic [Linux User Guide](../../../dragonboard410c/LinuxUserGuide_DragonBoard.pdf).	

#### Windows

Get ready for Windows IoT Core, set up your DragonBoard and build your first Windows IoT Core app. One you have [downloaded and installed](http://ms-iot.github.io/content/en-US/Downloads.htm) this operating system you can visit the [Microsoft Windows Dev Center](https://developer.microsoft.com/en-us/windows/iot) for instructions on how to get started with your first application. 




