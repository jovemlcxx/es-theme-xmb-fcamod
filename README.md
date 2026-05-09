# XMB Theme for EmulationStation

![Platform](https://img.shields.io/badge/Platform-EmulationStation-purple)
![Style](https://img.shields.io/badge/Style-XMB-blue)

A premium, high-performance XMB-styled theme designed specifically for handheld devices. This theme brings the classic console interface experience to your system with smooth animations and a refined layout.
Optimized for **FCAMOD,** a fork of EmulationStation by [christianhaitian](https://github.com/christianhaitian/EmulationStation-fcamod).

![Preview](./xmb.png)

## 🌟 Features

- **Classic XMB Interface:** Faithful recreation of the XMB (Cross Media Bar) experience found on PSP/PS3.
- **Multi-Aspect Ratio Support:** Optimized layouts for different screen formats:
  - **4:3:** Perfect for R36S, RG351MP, and other standard handhelds (640x480).
  - **1:1:** Tailored for square screens like the RGB30 (720x720).
- **Premium Dark Aesthetics:** Features a sleek, modern dark color palette for a comfortable and premium viewing experience.
- **Dynamic Backgrounds:** Support for both static images and animated video backgrounds.
- **High-Quality Typography:** Uses *FOT-NewRodin Pro* fonts for a premium, native feel.
- **Optimized for FCAMOD:** Leverages advanced grid layouts and video delay features supported by the FCAMOD engine.

## 📂 Installation

1. Connect to your device via SCP or SFTP.
2. Navigate to your themes directory (usually `/roms/themes/` or `~/.emulationstation/themes/`).
3. Copy the `es-theme-xmb-fcamod` folder into the themes directory.
4. In EmulationStation, go to **UI Settings** > **Theme Set** and select `es-theme-xmb-fcamod`.
5. Go to **UI Settings** > **Theme Configuration** to customize:
   - **Aspect Ratio:** Select the one that matches your device (4:3 or 1:1).
   - **Wallpaper:** Select the number corresponding to your custom background (1 to 20).

## 🖼️ Wallpaper Customization

The theme supports up to 20 custom wallpapers (Images and/or Videos). You can easily add your own:

1. **Prepare your files:** 
   - Static images must be in **.png** format.
   - Animated backgrounds must be in **.mp4** format.
2. **Rename the files:**
   - Follow the pattern `bg_{number}.png` or `bg_{number}.mp4`.
   - Example: `bg_1.png`, `bg_1.mp4`, etc.
3. **Copy to the theme folder:**
   - Place your files inside the `_inc/background/` directory.
4. **Select the wallpaper on menu:**
   - Open the emulationstation menu, go to **Theme Configuration** > **Wallpaper** and choose the number corresponding to your file.

## 🛠️ Credits & References

This project utilizes assets, logic, and design inspiration from several amazing community projects:

- **Assets:** Icons and UI elements sourced from the [RetroArch Assets](https://github.com/libretro/retroarch-assets) repository.
- **Base Project:** [anthonycaccese/xmb-menu-es-de](https://github.com/anthonycaccese/xmb-menu-es-de) - Primary structural reference, adapted for compatibility with the legacy FCAMOD engine.
    - [mohamedhany1024/ps3-xmb-web](https://github.com/mohamedhany1024/ps3-xmb-web) - Logic and layout reference for the PS3 XMB style.
    - [RobZombie9043/xmb-es-de](https://github.com/RobZombie9043/xmb-es-de) - Additional layout inspirations.
    - [lcdyk0517/arkos4clone](https://github.com/lcdyk0517/arkos4clone) - Structural guidance for ArkOS compatibility.
- **Background Video:** Animated background created by **TizzyT** ([Source Video](https://youtu.be/69RqDjCYiek)).

---

*Developed for the Retro Gaming community.*
