# XMB Theme for EmulationStation

![Platform](https://img.shields.io/badge/Platform-EmulationStation-purple)
![Style](https://img.shields.io/badge/Style-XMB-blue)
[![Github](https://img.shields.io/badge/Github-Repository-black?logo=github)](https://github.com/jovemlcxx/es-theme-xmb-fcamod)

A theme inspired by the XMB style, designed specifically for consoles using the EmulationStation frontend. This theme brings the classic console interface experience to your system with clean, optimized code and a refined layout.

**Official Repository:** [github.com/jovemlcxx/es-theme-xmb-fcamod](https://github.com/jovemlcxx/es-theme-xmb-fcamod)

Optimized for **FCAMOD,** a fork of EmulationStation created by [christianhaitian](https://github.com/christianhaitian/EmulationStation-fcamod)

![Preview](./xmb.png)

## 💻 Supported Systems

Fully compatible and optimized to run on the following distributions:
- [ArkOS](https://github.com/christianhaitian/arkos)
- [dArkOS](https://github.com/christianhaitian/dArkOS)
- [ArchR](https://github.com/archr-linux/Arch-R)
- [Batocera](https://batocera.org/)
- And other systems based on the FCAMOD engine.

## 🌟 Features

- **Classic XMB Interface:** A close recreation of the XMB (Cross Media Bar) experience found on PSP/PS3.
- **Multiple Aspect Ratios Support:** Layouts optimized for different screen formats:
  - **4:3:** Perfect for R36S, RG351MP, and other standard handhelds (640x480).
  - **1:1:** Tailor-made for square screens like the RGB30, R36 Ultra, and R36 Pro Max (720x720).
- **Dark Mode Support:** Features an elegant and modern dark color palette for a comfortable visual experience.
- **Dynamic Backgrounds:** Support for static backgrounds (.png images) and animated backgrounds (.mp4 videos).
- **High-Quality Typography:** Uses the *FOT-NewRodin Pro* fonts for a premium and authentic look.
- **Optimized for FCAMOD:** Takes advantage of advanced grid layouts and video delay features supported by the FCAMOD engine.

## 📂 Installation

1. Connect to your device via SCP or SFTP.
2. Navigate to your themes directory (usually `/roms/themes/` or `~/.emulationstation/themes/`).
3. Copy the theme folder to this directory. 
   - **Note:** The folder must be named `es-theme-xmb-fcamod` or `es-theme-xmb-fcamod-main` (if downloaded directly from GitHub).
4. In EmulationStation, go to **UI Settings** > **Theme Set** and select the theme.
5. Go to **UI Settings** > **Theme Configuration** to customize:
   - **Aspect Ratio:** Select the format that matches your device (4:3 or 1:1).
   - **System Layout:** Choose between **Horizontal (Classic XMB)** or **Vertical (Left Bar)**.
   - **Color Scheme:** Choose between **Dark** or **Light**.
   - **Wallpaper:** Select the number corresponding to your custom background (from 1 to 20).

## 🖼️ Wallpaper Customization

The theme supports up to 20 custom wallpapers (Images and Videos). **Please note that only one wallpaper (`bg_1.png` and `bg_1.mp4`) is included by default.**

> **⚠️ Performance Tip:** If you experience slowdowns or frame drops in your device's menus, it is highly recommended to delete the `bg_1.mp4` file. Background videos can be heavy and cause performance drops on devices with less than 1GB of RAM.

You can easily add your own files:

### About Resolution and Aspect Ratio
The theme will automatically stretch images and videos to fill 100% of your console's screen. Therefore, to prevent your media from looking distorted, **make sure the resolution of your image and video matches the aspect ratio of your device's screen**.
- For **4:3** screen consoles (like the R36S, Miyoo Mini), we recommend media in **1024x768** or **640x480** resolution.
- For **1:1** screen consoles (like the R36 Ultra and R36 Pro Max), we recommend creating perfectly square media (e.g., **720x720** or **1080x1080**).

### Step-by-step to add files:

1. **Prepare your files:** 
   - Static images must be in **.png** format.
   - Animated backgrounds must be in **.mp4** format.
2. **Rename the files:**
   - Follow the pattern `bg_{number}.png` or `bg_{number}.mp4`.
   - Example: `bg_1.png`, `bg_1.mp4`, etc.
3. **Copy to the theme folder:**
   - Place your files inside the `_inc/background/` directory.
4. **Select the wallpaper in the menu:**
   - Open the EmulationStation menu, go to **Theme Configuration** > **Wallpaper** and choose the number corresponding to your file.

## 🛠️ Credits and References

This project uses assets, logic, and design inspirations from several amazing community projects:

- **Assets:** Icons and interface elements taken from the [RetroArch Assets](https://github.com/libretro/retroarch-assets) repository.
- **Base Project:** [anthonycaccese/xmb-menu-es-de](https://github.com/anthonycaccese/xmb-menu-es-de) - Main structural reference, adapted for compatibility with the older FCAMOD engine.
    - [mohamedhany1024/ps3-xmb-web](https://github.com/mohamedhany1024/ps3-xmb-web) - Logic and layout reference for the PS3 XMB style.
    - [RobZombie9043/xmb-es-de](https://github.com/RobZombie9043/xmb-es-de) - Additional layout inspirations.
    - [lcdyk0517/arkos4clone](https://github.com/lcdyk0517/arkos4clone) - Structural guidance for ArkOS compatibility.
- **Background Video:** Animated background created by **TizzyT** ([Original Video](https://youtu.be/69RqDjCYiek)).

---

*Developed for the Retro Gaming community.*
