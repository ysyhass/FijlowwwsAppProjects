# FijlowwwsAppProjects

Cross-OEM Android app ports and compatibility fixes by @fijlowwwreal.

This repository contains apps extracted from ColorOS, OxygenOS, and HyperOS, then modified, patched, or fixed to improve compatibility on other Android devices and operating systems.

«Note: These apps were not originally designed for every device listed here. Some features may depend on OEM-specific frameworks, services, libraries, permissions, or system APIs.»

(You can use these as references at any time.)

---

📦 Repository Contents

Platform| Apps
ColorOS 16| 9
ColorOS 17| 13
OxygenOS 16| 1
HyperOS 3| 6
HyperOS 4| 4

---

🎨 ColorOS 16

Original ColorOS 16 applications adapted for use outside of ColorOS.

Calculator — 16.3.6

Status: 🟢 Stable

- File: "ColorOS16Calculator16.3.6.apk"
- App: Calculator
- Version: 16.3.6
- Original OS: ColorOS 16

Taken from APKMirror and patched to resolve crashes.

---

Calendar — 16.11.0

Status: 🟢 Stable

- File: "ColorOS16Calendar16.11.0.apk"
- App: Calendar
- Version: 16.11.0
- Original OS: ColorOS 16

Taken from APKMirror and patched to resolve crashes.

---

Clock — 16.18.8

Status: 🟠 Unstable

- File: "ColorOS16Clock16.18.8.apk"
- App: Clock
- Version: 16.18.8
- Original OS: ColorOS 16

Currently the most stable ColorOS 16 Clock build tested.

Known issues

- Alarm screen does not appear.
- Navigation bar can bleed into application elements.
- Not recommended as a primary clock application.

---

My Files — 16.4.12

Status: 🟢 Stable

- File: "ColorOS16MyFiles16.4.12.apk"
- App: My Files
- Version: 16.4.12
- Original OS: ColorOS 16

Can be used as a primary file manager.

Known issues

- Selecting the Clean button on the Internal Storage / All Files card may crash the application.

---

Notes — 16.2.32

Status: 🟢 Highly Stable

- File: "ColorOS16Notes16.2.32.apk"
- App: Notes
- Version: 16.2.32
- Original OS: ColorOS 16

Can be used as a primary notes application.

Known issues

- Drawing/handwriting mode may freeze.

---

Photos — 16.35.10

Status: 🟢 Stable

- File: "ColorOS16Photos16.35.10.apk"
- App: Photos
- Version: 16.35.10
- Original OS: ColorOS 16

Very stable and suitable for use as a primary photos application.

---

Recorder — 16.17.2

Status: 🟠 Unstable

- File: "ColorOS16Recorder16.17.2.apk"
- App: Recorder
- Version: 16.17.2
- Original OS: ColorOS 16

Known issues

- Recording does not work correctly because required libraries are missing.
- Not recommended as a primary recording application.

---

Weather — 16.41.2

Status: 🟢 Stable

- File: "ColorOS16Weather16.41.2.apk"
- App: Weather
- Version: 16.41.2
- Original OS: ColorOS 16

Can be used as a primary weather application.

Known issues

If the application cannot find your location, refresh the weather page by pulling down. It may take several refreshes before the location loads.

---

Weather Service — 16.28.0

Status: 🟡 Stable-ish

- File: "ColorOS16WeatherService16.28.0.apk"
- App: Weather Service
- Version: 16.28.0
- Original OS: ColorOS 16

Background service used by the ColorOS Weather application.

Known issues

- May crash occasionally.
- Installation is generally unnecessary unless required by the Weather application.

---

🌈 ColorOS 17

ColorOS 17 applications ported from ColorOS 17, including modified builds designed to improve compatibility outside of ColorOS.

Patch Series

COS17-PS0_1

Patch: "COS17-PS0_1"
Patch date: September 21, 2026
Patch time: 26 minutes 6 seconds
Patch author: @fijlowwwreal

Patch purpose

- Makes applications identify themselves as running on ColorOS 17.
- Improves compatibility with ColorOS 17-specific UI behavior.
- Fixes various application crashes.
- Modifies system/OEM checks used by affected applications.

«The patched applications remain based on the original ColorOS 17 applications. The patch changes how the applications behave or identify their environment; it does not turn the host device into ColorOS.»

Patched releases

Application| Patched file
Calculator| "ColorOS17Calculator17.2.14_17patch.apk"
Calendar| "ColorOS17Calendar17.3.50_17patch.apk"
Clock| "ColorOS17Clock17.6.70_17patch.apk"
Compass| "ColorOS17Compass17.3.12_17patch.apk"
Documents| "ColorOS17Documents17.1.26_17patch.apk"
My Files| "ColorOS17MyFiles17.9.12_17patch.apk"
Notes| "ColorOS17Notes17.0.20_17patch.apk"
Phone Manager| "ColorOS17PhoneManager17.3.13_Fixed-17patch.apk"
Weather| "ColorOS17Weather17.6.4_17patch.apk"
Weather Services| "ColorOS17WeatherServices17.6.4_17patch.apk"

---

Calculator — 17.2.14

Status: 🟢 Stable

Original: ColorOS 17

- Original: "ColorOS17Calculator17.2.14.apk"
- Patched: "ColorOS17Calculator17.2.14_17patch.apk"
- Version: 17.2.14

---

Calendar — 17.3.50

Status: 🟢 Stable

Original: ColorOS 17

- Original: "ColorOS17Calendar17.3.50.apk"
- Patched: "ColorOS17Calendar17.3.50_17patch.apk"
- Version: 17.3.50

---

Clock — 17.6.70

Status: 🟠 Unstable

Original: ColorOS 17

- Original: "ColorOS17Clock17.6.70.apk"
- Patched: "ColorOS17Clock17.6.70_17patch.apk"
- Version: 17.6.70

Known issues

- Alarm screen does not appear.

---

Compass

17.0.0

Status: 🟢 Stable

- File: "ColorOS17Compass17.0.0.apk"
- Version: 17.0.0
- Original OS: ColorOS 17 Beta

17.3.12

Status: 🟢 Stable

- Original: "ColorOS17Compass17.3.12.apk"
- Patched: "ColorOS17Compass17.3.12_17patch.apk"
- Version: 17.3.12
- Original OS: ColorOS 17

---

Documents — 17.1.26

Status: 🟢 Stable

- Original: "ColorOS17Documents17.1.26.apk"
- Patched: "ColorOS17Documents17.1.26_17patch.apk"
- Version: 17.1.26
- Original OS: ColorOS 17

---

My Files — 17.9.12

Status: 🟢 Stable

- Original: "ColorOS17MyFiles17.9.12.apk"
- Patched: "ColorOS17MyFiles17.9.12_17patch.apk"
- Version: 17.9.12
- Original OS: ColorOS 17

---

Notes — 17.0.20

Status: 🟢 Stable

- Original: "ColorOS17Notes17.0.20.apk"
- Patched: "ColorOS17Notes17.0.20_17patch.apk"
- Version: 17.0.20
- Original OS: ColorOS 17

Known issues

- Add button is displayed as a square.
- Drawing/handwriting crashes the application.

---

Phone Manager — 17.3.13

Original build

Status: 🟠 Unstable

- File: "ColorOS17PhoneManager17.3.13.apk"
- Version: 17.3.13
- Original OS: ColorOS 17 Beta

Known issues

- Most widgets are broken.
- Storage cleaner does not work correctly.
- Storage cleaner may report 0 bytes.
- Media is not detected correctly.
- Additional ColorOS/Oplus functionality remains unavailable.

Fixed build

Status: 🟡 Stable-ish

- File: "ColorOS17PhoneManager17.3.13_Fixed.apk"
- Version: 17.3.13

Changes

- Storage cleaner now works.
- Process cleaner still reports 0 bytes because of Android system limitations.
- Widgets remain broken.

Fixed + COS17 patch

- File: "ColorOS17PhoneManager17.3.13_Fixed-17patch.apk"

This combines the fixed Phone Manager build with the "COS17-PS0_1" patch.

---

Photos — 17.8.40

Status: 🟢 Stable

- File: "ColorOS17Photos17.8.40.apk"
- Version: 17.8.40
- Original OS: ColorOS 17

---

Secure Keyboard — 17.0.4

Status: 🟢 Stable

- File: "ColorOS17SecureKeyboard17.0.4.apk"
- Version: 17.0.4
- Original OS: ColorOS 17

Known issues

- Does not automatically switch to the Secure Keyboard.
- Must be manually selected as the active keyboard.
- Currently mainly provides the ColorOS-style UI/visual experience.

---

Weather — 17.6.4

Status: 🟢 Stable

- Original: "ColorOS17Weather17.6.4.apk"
- Patched: "ColorOS17Weather17.6.4_17patch.apk"
- Version: 17.6.4
- Original OS: ColorOS 17

---

Weather Services — 17.6.4

Status: 🟢 Stable

- Original: "ColorOS17WeatherServices17.6.4.apk"
- Patched: "ColorOS17WeatherServices17.6.4_17patch.apk"
- Version: 17.6.4
- Original OS: ColorOS 17

---

🔴 OxygenOS 16

Documents — 16.8.32

Status: 🟢 Stable

- File: "OxygenOS16Documents16.8.32.apk"
- Version: 16.8.32
- Original OS: OxygenOS 16

Can be used as a primary document application.

Known issues

- Creating a file may crash the application.

---

🟠 HyperOS 3

App| Version| File
Calculator| 16.0.9| "HyperOS3Calculator16.0.9.apk"
Clock| 17.22.0| "HyperOS3Clock17.22.0.apk"
Gallery Editor| G2.4.0.5.2| "HyperOS3GalleryEditorG2.4.0.5.2.apk"
Gallery| G4.3.1.18| "HyperOS3GalleryG4.3.1.18.apk"
Recorder| 7.8.7.1| "HyperOS3Recorder7.8.7.1.apk"
Weather| G17.0.3.26| "HyperOS3WeatherG17.0.3.26.apk"

«Compatibility information for these builds is still being documented.»

---

🟣 HyperOS 4

App| Version| File
Calendar| G18.0.6| "HyperOS4CalendarG18.0.6.apk"
Compass| 17.1.3.0| "HyperOS4Compass17.1.3.0.apk"
File Manager| V1-260253| "HyperOS4File ManagerV1-260253.apk"
Notes| 3.2.2.7| "HyperOS4Notes3.2.2.7.apk"

«Compatibility information for these builds is still being documented.»

---

📋 Status Legend

Status| Meaning
🟢 Stable| Generally usable with no major known issues
🟡 Stable-ish| Mostly usable but has notable limitations
🟠 Unstable| Works partially but has significant issues
🔴 Broken| Does not currently function properly
⚪ Untested| Compatibility has not been documented yet

---

🛠️ Porting / Patch Notes

These applications may rely on proprietary OEM components such as:

- Oplus / Oppo framework APIs
- ColorOS system services
- OEM-specific libraries
- Proprietary providers
- OEM permissions
- System properties
- Widgets and widget providers
- Vendor-specific storage APIs
- OEM activity/task-management APIs

As a result, an application may launch successfully while individual features remain broken.

A Stable status does not mean every feature of the original application is available.

---

📁 File Naming

Files generally follow this format:

<OS><App><Version>.apk

Patched builds:

<OS><App><Version>_<Patch>.apk

Fixed builds:

<OS><App><Version>_Fixed.apk

Combined fixed + patched builds:

<OS><App><Version>_Fixed-<Patch>.apk

Example:

ColorOS17PhoneManager17.3.13_Fixed-17patch.apk

---

⚠️ Disclaimer

These applications are provided for research, compatibility testing, customization, and educational purposes.

They are originally developed for their respective OEM Android distributions and may depend on proprietary system components.

Use at your own risk. Always keep a backup of your original applications before replacing or modifying system software.

---

👤 Credits

Ports / patches: @fijlowwwreal

TikTok: @fijlowwwreal

More ports and compatibility patches will be added as testing continues.
