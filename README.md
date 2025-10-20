# GALAXY-AI-FOR-A35
Magisk modules to enable and port Galaxy AI features on the Samsung Galaxy A35 5G

![Project Status](https://img.shields.io/badge/status-in--development-yellow)
![Platform](https://img.shields.io/badge/platform-Android%20(Samsung%20Galaxy%20A35)-blue)
![Requires](https://img.shields.io/badge/requires-Root%20(Magisk)-red)
![License](https://img.shields.io/badge/license-MIT-green)

A collection of Magisk modules and system tweaks to enable, port, and enhance AI-related features on the Samsung Galaxy A35 5G (SM-A356E).

---

## 🚀 Features

This project aims to bring a suite of AI-powered enhancements and hidden features to the Galaxy A35.

- [✔] **UI Enhancements:** Enable system-wide blur effects and other visual tweaks.
 - > **Drawback:** Enabling live blur is GPU-intensive. You may notice a slight increase in device temperature and occasional lag in home screen animations. For this reason, the live blur has been intentionally limited to core system UI (like the widgets Blur) to avoid severe performance issues.
- [✔] **Generative AI Features:** Port or enable features like AI Wallpaper, Photo Remaster enhancements, and more.
- [✔] **Performance Tweaks:** Optimize system properties for better performance on-device.

## 🐛 Known Bugs

Please be aware of the following issues currently under investigation. If you can provide logs (`logcat`) for these crashes, please open an issue!

- **Generative Move Crash:** Using the "Generative Move" feature in the photo editor to reposition objects may cause the Gallery app to force close.
- **AI Cartoonizer Effect Crash:** Applying the AI-based "Cartoon" or "Toonify" effect from the Gallery labs or editor can result in a crash.
- **General On-Device Processing Crash:** Some intensive, on-device AI tasks (like complex object removal or video effects) may crash intermittently. This is likely due to missing libraries.

## 🗺️ Roadmap (Future Scope)

Here are some of the features and improvements planned for the future:

- [ ] **Porting Flagship Features:** Investigate porting more advanced AI features from the Galaxy S series, such as battery health ML or Live Translate, if feasible.
- [ ] **AIO Module:** Develop an "All-in-One" Magisk module that combines the most popular tweaks into a single, easy-to-install package.
- [ ] **Performance Profiles:** Create modules to enable different system performance profiles (e.g., "Battery Saver AI," "Max Performance AI").
- [ ] **Deeper Camera Integration:** Explore modifications to the camera HAL or app to unlock hidden modes or improve image processing.
- [ ] **Script-based Installer:** Develop a script that allows users to pick and choose which features they want to install.

## ⚠️ Disclaimer

Modifying your device's system files carries inherent risks. While these modules are tested, you are solely responsible for any issues that may arise, including but not limited to:
- Bootloops
- Application instability
- Voiding your device warranty

**Always make a full backup of your data before installing any modifications.**

## ✅ Prerequisites

- **Device:** Samsung Galaxy A35 5G (SM-A356E)
- **Bootloader:** Must be unlocked.
- **Root:** Magisk must be installed and working correctly.
- **Knowledge:** Basic understanding of Magisk, `adb`, and how to recover from a bootloop.

## 🛠️ Installation

1. Go to the [Releases](https://github.com/StarDust-Git-Code/Galaxy-AI-for-A35/releases) page of this repository.
2. Download the `.zip` file for the feature you want to install.
3. Open the Magisk app on your phone.
4. Go to the `Modules` tab.
5. Tap `Install from storage` and select the downloaded `.zip` file.
6. Reboot your device once the installation is complete.

## 💖 Support This Project

If you find this project helpful and want to support its continued development, please consider a small donation. It helps cover the costs of development and testing.

- **UPI (Supports International):** `mailboxofirshadahamed-1@okhdfcbank`

   ![UPI QR Code](assets/upi-qr.jpg)

  
- **Bitcoin (Lightning Wallet):** `curvymaid35@walletofsatoshi.com`

   ![Lightning Wallet QR Code](assets/lightning-qr.jpg)

  
## 📂 Repository Structure

- **/modules**: Contains the individual, flashable Magisk module projects.
- **/scripts**: Helper scripts for development or automation.
- **/system-files**: Contains original and modified system files for reference (e.g., `floating_feature.xml`).
- **/docs**: In-depth documentation and guides.

## 🤝 Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
