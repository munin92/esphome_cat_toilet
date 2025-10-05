# Katzenklo (Fork of SmartCat Toilet)

This repository is a **fork / adaptation** of the **SmartCat Toilet** project by Dominik (MakerWorld).  
I’ve replaced the original firmware with an **ESPHome + ESP32** implementation and am working to improve reliability, features, and integration with Home Assistant.

## About the Original

The SmartCat Toilet is a fully 3D-printed, automated cat litter box that:

- Searches for its home position on boot  
- Measures live weight via sensor  
- Starts cleaning after cat leaves + a delay  
- Stops cleaning immediately if cat re-enters  
- Returns to home position after cleaning  
- Uses ~12 kg of filament and modular parts  

Visit the original project: [SmartCat Toilet on MakerWorld](https://makerworld.com/de/models/1343408-smartcat-toilet)

## What This Fork Adds / Changes

- Firmware using **ESPHome** (ESP32) for sensors, motor control, logic  
- Integration-ready with Home Assistant  
- Configuration via YAML  
- Safety improvements, usability tweaks, diagnostics  

## Usage / Setup

1. Clone this repo  
2. Set your Wi-Fi / secrets  
3. Flash via ESPHome  
4. Mount to the SmartCat mechanical build  
5. Calibrate sensors (tare, thresholds)  
6. Let it run!  

Continue with sensors, automations, warnings, etc. (similar to the README we drafted earlier).

---

## 🙏 Attribution and Respect

- All mechanical / 3D model credit goes to **Dominik (Dododomme)**, MakerWorld.  
- Be sure to **respect the original license terms** before redistributing or commercializing.  
- If you add significant improvements (software or hardware), consider contributing back or coordinating with the original author.

