#  ThinkPad X260 OpenCore

## What is this repo?
This repository contains files for my OpenCore Hackintosh build. I'm running it on my ThinkPad X260, so it doesn't contain any kexts/SSDTs/tweaks that would be recommended/required on other devices. It could work on other 2016-era ThinkPads (T460/560, X1C Gen 4 etc.), albeit with some defects (USB/display/Ethernet ports not working, wonky power management, sleep not working, YMMV).

## What this repo is **NOT**?
It's not a guide. 
If you're not familiar with basic Hackintoshing concepts, or if you don't know what to do with the files contained in this repository, you're better off reading [Dortania's OpenCore guide](https://dortania.github.io/OpenCore-Install-Guide/) in its entirety.

## Anything else?

The MountEFI command contained in this repo can be found on [corpnewt's repository](https://github.com/corpnewt/MountEFI) - it's probably more up to date, I contained it in my repo for ease of use.
[ThinkPad T460s Hackintosh guide by simprecicchiani](https://github.com/simprecicchiani/ThinkPad-T460s-macOS-OpenCore) was how I started this config, however at one point I decided to start fresh. However, after a while I decided to start fresh and build a new EFI using Dortania's guide, but I copied some ideas and fixes from simprecicchiani's guide, so I figured I should give them credit.

I want to make it clear that there's no warranty. This config is far from being finished, and even though it's usable as a daily driver (apart from some power management and sleep-mode issues), DATA LOSS MIGHT OCCUR. Remember to back everything up, and only use this config if you're OK with 1. losing all your data, 2. randomly not being able to boot, 3. dealing with some random glitches and quirks.
I'm making it sound more serious than it actually is, but consider yourselves warned.

## What hardware are you using?
My X260's hardware is:
- Intel i5-6300U, 
- 16GB of RAM, 
- 768p TN display, 
- stock Intel WLAN/BT (Dual Band Wireless-AC 8260) fully working with Airportitlwm.kext
- non-backlit ISO-layout keyboard (can't test if backlight works)
- no fingerprint reader (can't test if that works either)
I also have a dock - I haven't tested all of the ports, but the Ethernet, VGA output and dock charging works (todo: check all ports)

## To-do list

- Fix sleep and power management
- Check all dock ports
- ...find stuff to add to this list, I guess
