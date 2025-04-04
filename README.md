# Colorful (Simplified) for ES-DE

This is simplified take on the Colorful theme which was originally created by [viking](https://forums.launchbox-app.com/profile/70421-viking/) & [faeran](https://forums.launchbox-app.com/profile/76940-faeran/) for Launchbox.

Most artwork was originally created by viking & faeran (_additional artwork credits can be found in the credits section below_). I translated things for the theming engine used by ES-DE. The original version of the Colorful theme for Launchbox can be found [here](https://forums.launchbox-app.com/files/file/2081-colorful-bigbox-theme)

### Changes Made

- Translated and rewrote all Launchbox specific aspects to make the theme compatible with ES-DE
- Updated system image names to match the standard used by ES-DE
- Created images & color schemes for additional systems supported by ES-DE
- Added support for ES-DE capabilities such as badges
- Embedded the ES-DE [system-metadata](https://gitlab.com/es-de/themes/system-metadata) repository to power system description, release year and color details

## **Preview**

| System View |
|----|
| ![Screenshot 2025-03-02 at 1 40 04 PM](https://github.com/user-attachments/assets/9d1d32e0-77e2-4088-83ac-d73d64d675cc) |

| Gamelist View: List | Gamelist View: List with Metadata |
|----|----|
| ![Screenshot 2025-03-02 at 1 41 29 PM](https://github.com/user-attachments/assets/09cda077-22e4-4dc8-af38-dc289f82698f) | ![Screenshot 2025-03-02 at 1 41 37 PM](https://github.com/user-attachments/assets/1ff787bc-b5a3-4853-9bf7-780ecd57b912) |

## **Configuration Options**

The theme has a simple set of options that can be changed directly from the UI Settings menu of ES-DE 

### **Theme Variants**

- `Theme Variant` - sets the layout used for the gamelist view when media & metadata are scraped for your games.  There are a few variants to choose from:
   - Lists - There are a few options available to allow for dfferent media to be displayed. Please select the one that best matches the media you have downloaded for your games.
      - `List: Boxart` - Displays Boxart
      - `List: Screenshot` - Displays Screenshot
      - `List: Screenshot + Marquee` - Displays Screenshot with a Marquee overlay
      - `List: Title Screen` - Displays Title Screen
      - `List: Physical Media` - Displays Physical Media
      - `List: Miximage` - Displays Miximage
      - `List: Metadata & Screenshot + Boxart` - Displays Metadata, Screenshot & Boxart
      - `List: Metadata & Screenshot + Marquee` - Displays Metadata, Screenshot & Marquee
      - `List: Metadata & Screenshot + Physical Media` - Displays Metadata, Screenshot & Physical Media

### **Theme Color Schemes**

- `Theme Color Scheme` - sets the color scheme that is used for the overall theme on all views.  There are 6 built in color schems:
   - `Colorful` - The default color scheme.  Displays a custom color for each system based on the Colorful media set.
   - `Colorful (Dark)` - Displays a custom color for each system based on the Colorful media set.
   - `OLED` - Sets a dark color scheme that displays for all systems
   - `Dark` - Sets a dark color scheme that displays for all systems
   - `Light` - Sets a light color scheme that displays for all systems
   - `RetroBright` - Sets a light color scheme that displays for all systems
   - `DMG` - Sets a light color scheme that displays for all systems
   - `Add-on (See Readme)` - Only choose this when you have installed one of the available add-ons.  Please read the [Add-ons](#add-ons) section below for more details.

#### Preview

| Colorful | Dark |
|:---:|:---:|
| ![Screenshot 2025-03-02 at 1 40 04 PM](https://github.com/user-attachments/assets/9d1d32e0-77e2-4088-83ac-d73d64d675cc) | ![Screenshot 2025-03-02 at 1 43 55 PM](https://github.com/user-attachments/assets/45aed9f3-c7ca-4890-9ba8-60326a1ec29c) | 
| OLED | Light |
| ![Screenshot 2025-03-02 at 1 44 00 PM](https://github.com/user-attachments/assets/152e74a2-ca45-4285-ad70-5c4ec532765f) | ![Screenshot 2025-03-02 at 1 44 09 PM](https://github.com/user-attachments/assets/66d509b2-a20f-4a33-859f-c70c600a2451) |
| RetroBright | DMG |
| ![Screenshot 2025-03-02 at 1 44 15 PM](https://github.com/user-attachments/assets/a6a0cb12-5e02-4ddb-8227-7e907d634b43) | ![Screenshot 2025-03-02 at 1 44 21 PM](https://github.com/user-attachments/assets/6304c994-e69d-4450-a5e5-2acab764ebcc)

### **Theme Font Sizes**

- `Theme Font Size` - sets the size that text will render at. This can be helpful when using the theme on small screens.
   - Supported Font Sizes:
   - `Medium` - Default size, good for computer monitors and tv.
   - `Large` - Larger size, good for small handheld screens under 6 inches in size.

### **Theme Aspect Ratios**

- `Theme Aspect Ratio` - sets the aspect ratio to match your display. This should happen automatically but can also be set manually if needed.
   - Supported Aspect Ratios:
   - `16:9`
   - `16:10`
   - `4:3`
   - `1:1`

#### Preview

| 16:9 System View | 16:9 List View | 16:9 List View Metadata |
|:---:|:---:|:---:|
| ![Screenshot 2025-03-02 at 1 40 04 PM](https://github.com/user-attachments/assets/9d1d32e0-77e2-4088-83ac-d73d64d675cc) | ![Screenshot 2025-03-02 at 1 41 29 PM](https://github.com/user-attachments/assets/09cda077-22e4-4dc8-af38-dc289f82698f) | ![Screenshot 2025-03-02 at 1 41 37 PM](https://github.com/user-attachments/assets/1ff787bc-b5a3-4853-9bf7-780ecd57b912) |
| 16:10 System View | 16:10 List View | 16:10 List View Metadata |
| ![Screenshot 2025-03-02 at 1 40 25 PM](https://github.com/user-attachments/assets/081ed1ff-0b1a-4344-9537-b620d709449f) | ![Screenshot 2025-03-02 at 1 41 08 PM](https://github.com/user-attachments/assets/5e245bc1-155e-4af8-b67b-831b231f3bc3) | ![Screenshot 2025-03-02 at 1 40 46 PM](https://github.com/user-attachments/assets/8ebe552b-f440-4da5-ae88-71c5b1d8943a) |
| 4:3 System View | 4:3 List View | 4:3 List View Metadata |
| ![Screenshot 2025-03-02 at 1 39 35 PM](https://github.com/user-attachments/assets/05a4b0d0-38e7-4313-a7c4-95f47b571ec5) | ![Screenshot 2025-03-02 at 1 42 49 PM](https://github.com/user-attachments/assets/7fc73c98-93c4-42fb-a8f9-34be43289ce5) | ![Screenshot 2025-03-02 at 1 42 42 PM](https://github.com/user-attachments/assets/7b416c1a-f032-48c4-84b4-1702381f384a) |
| 1:1 System View | 1:1 List View | 1:1 List View Metadata |
| ![Screenshot 2025-03-02 at 1 39 20 PM](https://github.com/user-attachments/assets/a6e97994-4971-4918-9de1-e128c063820e) | ![Screenshot 2025-03-02 at 1 43 14 PM](https://github.com/user-attachments/assets/3778fd37-13ce-4260-bc16-96fda524fac7) | ![Screenshot 2025-03-02 at 1 43 23 PM](https://github.com/user-attachments/assets/1d03df1c-0d6d-4336-90a1-07803c0a40e5) |

## Add-ons
- As of ES-DE v3.2.0 (or later) this theme has support for add-ons that can add additional functionality to an installed theme.
   - **Available add-ons:**
   - [1080p System Video](https://github.com/anthonycaccese/colorful-simplified-es-de-addon_1080p-system-video/releases/latest): Adds video playback (1080p assets) to the system view with videos from the Colorful platform video set (originally created by Viking for Launchbox).
   - [720p System Video](https://github.com/anthonycaccese/colorful-simplified-es-de-addon_720p-system-video/releases/latest): Adds video playback (720p assets) to the system view with videos from the Colorful platform video set (originally created by Viking for Launchbox).

## Additional Notes

### Versions for other ES forks
- If you use Batocera... then check out the version [here](https://github.com/anthonycaccese/colorful-simplified-es).  The Batocera version has most of the same base features.  It also adds some additional features such as the theming of the menu and the ability to toggle on/off the display of different media elements directly through the menu ui.

### Credits

- Most artwork originally created by [viking](https://forums.launchbox-app.com/profile/70421-viking/) & [faeran](https://forums.launchbox-app.com/files/file/2081-colorful-bigbox-theme)
- For systems that did not exist in the Colorful set; some were sourced from the great work done by [g-spawn](https://github.com/g-spawnPL) for the [ckau-book](https://github.com/CkauNui/ckau-book/tree/master) theme and they were edited to add transparency.
- OpenBOR sprites originally created by [DOA687](https://www.deviantart.com/doa687)
- M.U.G.E.N. sprites originally created by [mpadillathespriter](https://www.deviantart.com/mpadillathespriter)
- EasyRPG artwork originally created by [SeraphCircle](https://twitter.com/SeraphCircle)
- Doom artwork originally created by [azakachi-rd-17](https://www.deviantart.com/azakachi-rd-17)
- Quake artwork by [noorkabir](https://imgbin.com/png/TpRDSTtK/quake-champions-quake-iii-arena-quake-4-video-game-2017-dreamhack-winter-png)
- LowresNX artwork by [Duimon](https://forums.libretro.com/t/duimon-hsm-mega-bezel-graphics-and-presets-feedback-and-updates/28146/1049)
- The base folder image used to create the All Games, Favorites, Last Played and Custom Collections images was sourced from [Rick Patrick](https://www.softicons.com/designers/rick-patrick).
- The icons on the folder images were sourced from [FontAwesome](https://fontawesome.com/search?o=r&m=free)

## **License**

Creative Commons CC-BY-NC-SA - https://creativecommons.org/licenses/by-nc-sa/2.0/
You are free to share and adapt this theme as long as you provide attribution back as well share any updates you make under the same licence terms.
