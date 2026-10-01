# XMB Theme for EmulationStation

![Platform](https://img.shields.io/badge/Platform-EmulationStation-purple)
![Style](https://img.shields.io/badge/Style-XMB-blue)
[![Github](https://img.shields.io/badge/Github-Repository-black?logo=github)](https://github.com/jovemlcxx/es-theme-xmb-fcamod)

A theme inspired by the XMB (Cross Media Bar) of the PSP and PS3, made for handhelds running the EmulationStation frontend. It brings the classic console interface to your device with clean, optimized code and a layout faithful to the original.

**Official Repository:** [github.com/jovemlcxx/es-theme-xmb-fcamod](https://github.com/jovemlcxx/es-theme-xmb-fcamod)

Optimized for **FCAMOD**, the EmulationStation fork by [christianhaitian](https://github.com/christianhaitian/EmulationStation-fcamod).

![Preview](./xmb.png)

## 💻 Supported Systems

Validated against the frontend of each of these distributions:
- [ArkOS](https://github.com/christianhaitian/arkos) (including [arkos4clone](https://github.com/lcdyk0517/arkos4clone))
- [dArkOS](https://github.com/christianhaitian/dArkOS)
- [ArchR](https://github.com/archr-linux/Arch-R)
- [Batocera](https://batocera.org/)
- And other systems based on the FCAMOD engine.

## 🌟 Features

- **Classic XMB Interface:** System carousel with the same geometry as the PSP/PS3 XMB: five icons on screen, the selected one at a quarter of the screen with its physical media right below it.
- **PSP-style Game List:** Icon and name on every row. Names stay visible even while scrolling fast through hundreds of games.
- **Continuous Animated Background:** The background video keeps playing while you browse systems, instead of restarting on every move. It can be turned off in the settings.
- **375 System Icons:** Console and physical media icons for every system of ArkOS, dArkOS, ArchR and Batocera (see [System Icon Coverage](#-system-icon-coverage)).
- **Nintendo/Xbox or PlayStation Buttons:** The footer can show Nintendo/Xbox or PlayStation (○ ✕) button icons, with an option for devices with swapped A/B buttons.
- **Multiple Aspect Ratios:**
  - **4:3:** For R36S, RG351MP and other standard handhelds (640x480). Shows 3 games per screen.
  - **1:1:** For square screens like the RGB30, R36 Ultra and R36 Pro Max (720x720). Shows 5 games per screen.
- **Two Layouts:** Horizontal (Classic XMB) or Vertical (Left Bar).
- **Dark and Light Menus:** The settings menu, including on-screen keyboard text boxes (e.g. Wi-Fi password), follows the chosen color scheme.
- **Translated:** Theme settings are available in 26 languages (the button options are in English, Portuguese and Spanish so far).
- **High-Quality Typography:** Uses the *FOT-NewRodin Pro* fonts for an authentic look.

## 🆕 What's New

**New**
- **PlayStation button icons:** new **Button Icons** option (Nintendo / Xbox or PlayStation) for the footer. PlayStation icons follow the physical button position (A = ○, B = ✕).
- **Confirm Button (A/B) option:** the footer can show B as the confirm button for users who swapped A/B in the system settings.
- **PSP-style game list:** icon and name on every row, with bigger icons. 3 games per screen on 4:3 and 5 on 1:1. Game names now stay visible while scrolling fast.
- **System carousel matching the PSP/PS3 XMB:** same icon size, spacing and selected position as the original XMB, with the media icon centered below the selected system.
- **System icons for every distribution:** 375 console and media icons covering ArkOS, dArkOS, ArchR and Batocera, including missing ones recovered from the base theme and RetroArch Assets (Wolfenstein, DOOM and Cave Story floppies, Sega Pico, Commodore PET, Sharp MZ, arcade boards, game ports and more).
- **Batocera and ArchR compatibility:** the theme is validated against their frontend, and their extra languages are supported.

**Fixed**
- **Background video restarting:** the video no longer restarts when moving between systems, and the wallpaper image covers the gap while it loads.
- **Background Video option:** turning the video off now works (it was always on), and it really stops decoding instead of just hiding.
- **Unreadable text boxes in Dark mode:** typed text (e.g. Wi-Fi password) was white on a white box.
- **Systems without icon:** a missing icon left an empty slot (or black text on ArchR/Batocera); now every listed system has an icon, and unknown systems show their name in white.
- **Wrong icons:** several systems showed another system's icon (Sega Pico used PICO-8, Wolfenstein used DOOM, Daphne had no icon on Linux because of the file name case).
- **Translations:** Ukrainian (`ua`) users got English, and the two Portuguese blocks conflicted.
- **Cleanup:** removed settings and files the frontend never used (e.g. wallpapers 21–30, unsupported elements and properties).

## 📂 Installation

1. Connect to your device via SCP or SFTP.
2. Navigate to your themes directory (usually `/roms/themes/` or `~/.emulationstation/themes/`).
3. Copy the theme folder to this directory.
   - **Note:** The folder must be named `es-theme-xmb-fcamod` or `es-theme-xmb-fcamod-main` (if downloaded directly from GitHub).
   - **Updating:** delete the old theme folder before copying the new one, so files removed from the theme do not linger.
4. In EmulationStation, go to **UI Settings** > **Theme Set** and select the theme.
5. Go to **UI Settings** > **Theme Configuration** to customize it.

### ⚙️ Theme Configuration

| Option | Choices | Notes |
|---|---|---|
| **Aspect Ratio** | 4:3 / 1:1 | Pick the one that matches your screen. |
| **Background Video** | Enabled / Disabled | Disable it on slow devices; the static wallpaper is used instead. |
| **Wallpaper** | 1 to 20 | Only `1` is included; see [Wallpaper Customization](#%EF%B8%8F-wallpaper-customization). |
| **System Layout** | Horizontal (Classic XMB) / Vertical (Left Bar) | |
| **Color Scheme** | Dark / Light | Applies to the settings menu and on-screen keyboard. |
| **Button Icons** | Nintendo / Xbox, PlayStation | PlayStation follows the physical button position: A = ○, B = ✕. |
| **Confirm Button (A/B)** | A / B | Set to **B** if you swapped A/B in the system settings, so the footer shows the right button. |

## 🖼️ Wallpaper Customization

The theme supports up to 20 wallpapers, each with a static image and an optional animated video. **Only one wallpaper (`bg_1.png` and `bg_1.mp4`) is included by default.**

> **⚠️ Performance Tip:** If menus feel slow on your device, set **Theme Configuration** > **Background Video** to **Disabled**. Background videos can be heavy on devices with less than 1GB of RAM.

> **⚠️ Always provide the PNG:** Every video wallpaper (e.g. `bg_2.mp4`) needs a matching PNG (`bg_2.png`), ideally its first frame. The PNG is shown while the video loads and whenever the video is disabled; without it the screen stays black in those moments.

### About Resolution and Aspect Ratio
Images and videos are stretched to fill the whole screen. To avoid distortion, **use media with the same aspect ratio as your screen**:
- **4:3** consoles (like the R36S): **1024x768** or **640x480**.
- **1:1** consoles (like the R36 Ultra and R36 Pro Max): square media, e.g. **720x720** or **1080x1080**.

### Step-by-step to add files

1. **Prepare your files:**
   - Static images in **.png** format.
   - Animated backgrounds in **.mp4** format.
2. **Rename the files** following the pattern `bg_{number}.png` / `bg_{number}.mp4` (e.g. `bg_2.png`, `bg_2.mp4`).
3. **Copy them** into the theme's `_inc/background/` directory.
4. **Select the wallpaper:** open **Theme Configuration** > **Wallpaper** and choose its number.

## 🎮 System Icon Coverage

Every system has a console icon (carousel) and a physical media icon (cartridge, disc, tape, floppy...). Icons come, in order of preference, from the base theme [xmb-menu-es-de](https://github.com/anthonycaccese/xmb-menu-es-de), from [RetroArch Assets](https://github.com/libretro/retroarch-assets) (monochrome, or other styles converted to monochrome), or from an existing icon of the same hardware or game under another name (e.g. `pce-cd` → PC Engine CD, game ports → Ports, arcade boards → Arcade).

Systems with no icon in any of these sources use the generic controller icon.

| Distribution | Systems with icon | Specific icon | Generic icon |
|---|---|---|---|
| ArkOS (incl. arkos4clone) | 136/136 | 130 | 6 |
| dArkOS | 129/129 | 127 | 2 |
| ArchR | 136/136 | 134 | 2 |
| Batocera | 260/260 | 249 | 11 |

Systems currently using the generic icon:
- **ArkOS:** `bbk`, `gametank`, `krkr2`, `native32`, `onscripter`, `spmp8000`
- **dArkOS:** `gametank`, `onscripter`
- **ArchR:** `bk`, `ios`
- **Batocera:** `bk`, `camplynx`, `cgenie`, `commanderx16`, `gametank`, `laser310`, `mc10`, `pcw`, `pdp1`, `segaai`, `tvgames`

To add a missing icon, place `<system theme>.png` in `_inc/systems/controller/` (console) and `_inc/systems/physical-media/` (media). The file name must match the system's `<theme>` in `es_systems.cfg` exactly, **including upper/lower case**. A system that is in none of the lists above (e.g. a custom system) shows its name as text instead.

## ⚠️ Known Limitations

These come from the FCAMOD frontend itself and cannot be changed by a theme:

- **Sounds:** The theme includes the full XMB sound set, but stock FCAMOD only plays the navigation, launch and back sounds. The select, favorite and quick system select sounds are ignored.
- **Background while scrolling:** While you scroll fast through the game list, FCAMOD hides the selected game's background image and video; they come back as soon as you stop. Game names stay visible.
- **A/B swap:** The theme cannot detect the system's A/B swap setting, which is why the **Confirm Button (A/B)** option exists. The full native button legend was not used because it does not fit small screens in most languages.

## 🛠️ Credits and References

This project uses assets, logic, and design inspirations from several amazing community projects:

- **Base Project:** [anthonycaccese/xmb-menu-es-de](https://github.com/anthonycaccese/xmb-menu-es-de) - Main structural reference, carousel geometry, system and PlayStation button icons, and sounds, adapted for the older FCAMOD engine.
    - [mohamedhany1024/ps3-xmb-web](https://github.com/mohamedhany1024/ps3-xmb-web) - Logic and layout reference for the PS3 XMB style.
    - [RobZombie9043/xmb-es-de](https://github.com/RobZombie9043/xmb-es-de) - Additional layout inspirations.
    - [lcdyk0517/arkos4clone](https://github.com/lcdyk0517/arkos4clone) - Structural guidance for ArkOS compatibility.
- **Icons:** Additional system and media icons from the [RetroArch Assets](https://github.com/libretro/retroarch-assets) repository; extra button icons from [EmulationStation-fcamod](https://github.com/christianhaitian/EmulationStation-fcamod).
- **Background Video:** Animated background created by **TizzyT** ([Original Video](https://youtu.be/69RqDjCYiek)).

---

*Developed for the Retro Gaming community.*
