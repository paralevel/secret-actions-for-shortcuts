# $\huge\frak Secret\ Actions$

Collection of hidden actions in Shortcuts app on iOS 26 and macOS Tahoe 26
<br>
<br>
__Usage__
1. Click the action’s title to install a shortcut that contains only this action
2. Open the shortcut
3. Copy the action
4. Paste it into your own shortcut

<br>

> [!NOTE]
> - These actions are part extracted, part reverse engineered, copies of built in actions in Shortcuts app, which are for various reasons not selectable in the user interface
> - Probably nothing risky about them, but no guarantee
> - Confirmed to work on iOS 26 and macOS Tahoe 26 only

<br>

> [!TIP]
> It’s possible to extract some useful information from the output of the actions, for example the updated value of a parameter – by selecting a different detail for the output type <sup>[[iOS guide]](https://support.apple.com/guide/shortcuts/adjust-variables-apda36b9018b/ios) [[macOS guide]](https://support.apple.com/guide/shortcuts-mac/adjust-variables-apda36b9018b/mac)

<br>

<sup>_Disclaimer: This collection is built on a shortcut I posted here on [October 1 2025](https://github.com/paralevel/secret-actions-for-shortcuts/blob/4ef59fd3fc4b8bce28cfeb4a67e8d3c5d5f1b8ce/src/Secret%20Actions.unsigned.shortcut) (last updated [signed release](https://www.icloud.com/shortcuts/fa750e73f3df47c3a0483d050effb015)), and consists only of actions I personally have have been able to reverse engineer using data extracted from local system files_</sup>

<br>
<br>

> __iOS Settings__
###
[Wi-Fi › Power State](https://www.icloud.com/shortcuts/0eede8df51c14ffeaed1cf23d0efb7b6) ${\sf\small\color{DeepSkyBlue} iOS}$<br><sub>_To extract the value, change the output type [detail](https://support.apple.com/guide/shortcuts/adjust-variables-apda36b9018b/ios)_</sub><p>Get the Wi-Fi power state (Wi-Fi)

<br>

[Battery › Show Percentage](https://www.icloud.com/shortcuts/fb45c3d68f274b96a9ec8197ca5e03d0) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Toggle “Battery Percentage” (Battery)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup><br>

<br>

[Battery › Low Power Mode State](https://www.icloud.com/shortcuts/4e4831a68bc44d1386398a96bbc0b37d) ${\sf\small\color{DeepSkyBlue} iOS}$<br><sub>_To extract the value, change the output type [detail](https://support.apple.com/guide/shortcuts/adjust-variables-apda36b9018b/ios)_</sub><p>Get the Low Power Mode state (Battery)

<br>

[General › AirDrop By Bringing Devices Together](https://www.icloud.com/shortcuts/adda1b4a5e6c49d6b8faa5512dc0fc09) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Toggle the AirDrop setting “(Start Sharing By) Bringing Devices Together” (General › AirDrop)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[General › AirDrop Use Cellular Data](https://www.icloud.com/shortcuts/752d07f7888b4de8878e3a12fee1021e) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Toggle the AirDrop setting “(Out of Range) Use Cellular Data” (General › AirDrop)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Zoom Filter Type](https://www.icloud.com/shortcuts/ded5de5e0e924cd9a5df2c879c91c4a7) ${\sf\small\color{DeepSkyBlue} iOS}$<br><sub>_You need to have Zoom enabled to see any changes_</sub><p>Change filter type for “Zoom Filter” (Accessibility › Zoom › Zoom Filter)<p><sup>__Parameters__<br>`ZOOM_LENS_EFFECT_NONE` [None] • `ZOOM_LENS_EFFECT_BLACK_AND_WHITE` [Grayscale] • `ZOOM_LENS_EFFECT_BLACK_AND_WHITE_INVERTED` [Grayscale Inverted] • `ZOOM_LENS_EFFECT_HUE_ADJUST` [not present in Settings] • `ZOOM_LENS_EFFECT_LOW_LIGHT` [Low Light]</sup>

<br>

[Accessibility › Bold Text](https://www.icloud.com/shortcuts/28c297e31aa44a57ade8a538c5ffb0b9) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Toggle “Bold Text” (Accessibility › Display & Text Size)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Show Borders](https://www.icloud.com/shortcuts/d8068de66bb0456ab47abae46f3168a4) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Toggle “Show Borders” (Accessibility › Display & Text Size)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › On/Off Labels](https://www.icloud.com/shortcuts/e45bce4643f84226a6f65c19485f5b89) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Toggle “On/Off Labels” (Accessibility › Display & Text Size)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Differentiate Without Color](https://www.icloud.com/shortcuts/44d17ef4b0ca4e8ca02b5ceeb0a251e3) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Toggle “Differentiate Without Colors” (Accessibility › Display & Text Size)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Color Filter Type](https://www.icloud.com/shortcuts/f203b0c45a8a41a4b16418fd9e94e85a) ${\sf\small\color{DeepSkyBlue} iOS}$<br><sub>_Automatically also enables Color Filters; no Color Tint parameter_</sub><p>Change filter type for “Color Filters” (Accessibility › Display & Text Size › Color Filters)<p><sup>__Parameters__<br>`OFF` [Off] • `RED_ADJUST` [Red/Green filter (Protanopia)] • `GREEN_ADJUST` [Green/Red filter (Deuteranopia)] • `BLUE_ADJUST` [Blue/Yellow filter (Tritanopia)] • `GRAYSCALE` [Grayscale]</sup>

<br>

[Accessibility › Reduce Bright Effects](https://www.icloud.com/shortcuts/9702f5b4a5684b5f9e46f8b25776f4b5) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Toggle “Reduce Bright Effects” (Accessibility › Display & Text Size)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Dim Flashing Lights](https://www.icloud.com/shortcuts/6d7a0035987849d2a8d1a0bd4b2df36f) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Toggle “Dim Flashing Lights” (Accessibility › Display & Text Size)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Auto-Brightness](https://www.icloud.com/shortcuts/88b6505076d4414f8acdde41b20ba741) ${\sf\small\color{DeepSkyBlue} iOS}$<br><sub>_Only Turn Off or Turn On should be used and not Toggle, since toggling to On currently doesn't work_</sub><p>Toggle “Auto-Brightness” (Accessibility › Display & Text Size)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Reachability](https://www.icloud.com/shortcuts/627c03553f9346a08a3450879b09b51d) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Toggle “Reachability” (Accessibility › Touch)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Shake To Undo](https://www.icloud.com/shortcuts/85fe6428b7eb4f468521347603017ef3) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Toggle “Shake to Undo” (Accessibility › Touch)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Vibration](https://www.icloud.com/shortcuts/1b61d7c6ea6e4e76a303af565e7ebdd9) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Toggle “Vibration” (Accessibility › Touch)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Vibration State](https://www.icloud.com/shortcuts/6e674594a17c459bac5d9682dd6e0c48) ${\sf\small\color{DeepSkyBlue} iOS}$<br><sub>_To extract the value, change the output type [detail](https://support.apple.com/guide/shortcuts/adjust-variables-apda36b9018b/ios)_</sub><p>Get the Vibration state (Accessibility › Touch)

<br>

[Accessibility › Mono Audio State](https://www.icloud.com/shortcuts/09064156a69244db8746ce50831e3efe) ${\sf\small\color{DeepSkyBlue} iOS}$<br><sub>_To extract the value, change the output type [detail](https://support.apple.com/guide/shortcuts/adjust-variables-apda36b9018b/ios)_</sub><p>Get the Mono Audio state (Accessibility › Audio & Visual)

<br>

[Accessibility › Flash For Alerts In Silent Mode](https://www.icloud.com/shortcuts/e1800c743b92455aab52297e12aaf998) ${\sf\small\color{DeepSkyBlue} iOS}$<br><sub>_You need to have Flash for Alerts enabled to see any changes_</sub><p>Toggle “Flash in Silent Mode” (Accessibility › Audio & Visual › Flash for Alerts)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Flash For Alerts While Unlocked](https://www.icloud.com/shortcuts/919ef5ee6ddd42f894408cc416598417) ${\sf\small\color{DeepSkyBlue} iOS}$<br><sub>_You need to have Flash for Alerts enabled to see any changes_</sub><p>Toggle “Flash While Unlocked” (Accessibility › Audio & Visual › Flash for Alerts)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Sounds & Haptics › Haptics](https://www.icloud.com/shortcuts/da466ed63c784c17a35d29ffa5c45289) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Change “Haptics” (Sounds & Haptics)<p><sup>__Parameters__<br>Always Play • Play in Silent Mode • Don”t Play in Silent Mode • Never</sup>

<br>

[Sounds & Haptics › Show Silent Mode In Status Bar](https://www.icloud.com/shortcuts/cb6d50f0fe8d414391cea66e6ef129d8) ${\sf\small\color{DeepSkyBlue} iOS}$<br><sub>_Unavailable on devices with a physical silent switch_</sub><p>Toggle “Show in Status Bar” (Sounds & Haptics › Silent Mode)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Sounds & Haptics › Silent Mode State](https://www.icloud.com/shortcuts/7588f95ab06e4d81ae18647ae23b7baf) ${\sf\small\color{DeepSkyBlue} iOS}$<br><sub>_To extract the value, change the output type [detail](https://support.apple.com/guide/shortcuts/adjust-variables-apda36b9018b/ios) – doesn't work on devices with a physical silent switch_</sub><p>Get the Silent Mode state (Sounds & Haptics › Silent Mode)

<br>

[FaceTime › Silence Unknown Callers](https://www.icloud.com/shortcuts/83e6c26612be43f1a8aa7fa7c0a08eea) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Toggle “Silence Unknown Callers” (Apps › FaceTime)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>
<br>

> __macOS Settings__
###
[General › iPhone Widgets](https://www.icloud.com/shortcuts/b2f0d04dac3c481a9b397f852bb4698b) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “iPhone Widgets” (General › AirDrop & Continuity)<p><sup>__Parameters__<br>Off • On • Toggle</sup>

<br>

[Accessibility › Use Scroll Gesture With Modifier Keys To Zoom](https://www.icloud.com/shortcuts/0833b7dbdd7a4cf98fa67cdc858b78bf) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Use scroll gesture with modifier keys to zoom” (Accessibility › Zoom)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Differentiate Without Color](https://www.icloud.com/shortcuts/f29ea258a80540efb0b148a778da150f) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Differentiate without color” (Accessibility › Display)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Dim Flashing Lights](https://www.icloud.com/shortcuts/fbe73ad3a49d4543a494b60500aa7d7c) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Dim flashing lights” (Accessibility › Display)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Show Window Title Icons](https://www.icloud.com/shortcuts/28c9a1c4eab34893a8ae4cb4372b44c4) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Show window title icons” (Accessibility › Display)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Show Toolbar Button Shapes](https://www.icloud.com/shortcuts/203c0068de784d4d8bf9eb20aeb64e03) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Show toolbar button shapes” (Accessibility › Display)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Prefer Horizontal Text](https://www.icloud.com/shortcuts/80fe1ad89eaa4661a8ca76260659ec8a) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Prefer horizontal text” (Accessibility › Display)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Shake Mouse Pointer To Locate](https://www.icloud.com/shortcuts/bce6bf3eccee4cae933fdf439cfca6fb) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Shake mouse pointer to locate” (Accessibility › Display)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Color Filters › Filter Type](https://www.icloud.com/shortcuts/f982e3422d7142279168767fd4d6c6b8) ${\sf\small\color{DeepSkyBlue} macOS}$<br><sub>_You need to have Color Filters enabled to see any changes_</sub><p>Change “Filter type” (Accessibility › Display › Color Filters)<p><sup>__Parameters__<br>Grayscale • Red/Green filter (Protanopia) • Green/Red filter (Deuteranopia) • Blue/Yellow filter (Tritanopia) • Color Tint</sup>

<br>

[Accessibility › Vehicle Motion Cues](https://www.icloud.com/shortcuts/f0573f3582f74ab8a1334d0725e84c5c) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Vehicle Motion Cues” (Accessibility › Motion)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Mono Audio State]() ${\sf\small\color{DeepSkyBlue} macOS}$<br><sub>_To extract the value, change the output type [detail](https://support.apple.com/guide/shortcuts-mac/adjust-variables-apda36b9018b/mac)_</sub><p>Get the “Play stereo audio as mono” state (Accessibility › Audio)

<br>

[Accessibility › Flash The Screen When An Alert Sound Occurs](https://www.icloud.com/shortcuts/7f9e4a28d262482883e39a6a5e4cc2f6) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Flash the screen when an alert sound occurs” (Accessibility › Audio)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Accessibility › Spatial Audio Follows Head Movements](https://www.icloud.com/shortcuts/e0b343a71b00497eb665e8dc250b84d0) ${\sf\small\color{DeepSkyBlue} macOS}$<br><sub>_The toggle won't reflect the changed state until System Settings is restarted_</sub><p>Toggle “Spatial audio follows head movements” (Accessibility › Audio)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Appearance › Sidebar Icon Size](https://www.icloud.com/shortcuts/acef10e5216e4309846544eea4895fa3) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change “Sidebar Icon Size” (Appearance › Windows)<p><sup>__Parameters__<br>Small • Medium • Large</sup>

<br>

[Appearance › Tint Window Background With Wallpaper Color](https://www.icloud.com/shortcuts/b25b9dd7de0049c7a1795b018b1ffa96) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Tint window background with wallpaper color” (Appearance › Windows)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Appearance › Show Scroll Bars When](https://www.icloud.com/shortcuts/cbc83684138647239140196e76a500c4) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change “Show scroll bars” (Appearance › Windows)<p><sup>__Parameters__<br>Automatically based on mouse or trackpad • When scrolling • Always</sup>

<br>

[Appearance › Click In Scroll Bar To](https://www.icloud.com/shortcuts/94b30eeab6104e9282f964d18e6764e8) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change “Click in the scroll bar to” (Appearance › Windows)<p><sup>__Parameters__<br>Jump to the next page • Jump to the spot that’s clicked</sup>

<br>

[Desktop & Dock](https://www.icloud.com/shortcuts/55a45fe74e8742728c0aa959f8cf923e) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change one or more Desktop & Dock settings<p><sup>__Parameters__<br>Animate opening applications • Automatically hide and show the Dock • Window title bar double-click action • Magnification • Minimize windows into application icon • Minimized window animation • Dock position on screen • Show indicators for open applications • Show suggested and recent apps in Dock • Size</sup>

<br>

[Desktop & Dock › Desktop & Stage Manager](https://www.icloud.com/shortcuts/6ac72fbd32f04154aadb0f7787759f77) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change one or more “Desktop & Stage Manager” settings (Desktop & Dock › Desktop & Stage Manager)<p><sup>__Parameters__<br>Click wallpaper to show desktop • Visible Items In Stage Manager • Visible Items On Desktop • Show recent apps in Stage Manager • Show windows from an application • Stage Manager</sup>

<br>

[Desktop & Dock › Widgets](https://www.icloud.com/shortcuts/6aa49bbca57541a78cc2e17f3925d51f) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change one or more “Widgets” settings (Desktop & Dock › Widgets)<p><sup>__Parameters__<br>Show Widgets In Stage Manager • Show Widgets On Desktop • Dim widgets on desktop</sup>

<br>

[Desktop & Dock › Windows](https://www.icloud.com/shortcuts/a5f3efb31ef1489dbbaafd76d4b7600c) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change one or more “Windows” settings (Desktop & Dock › Windows)<p><sup>__Parameters__<br>Ask to keep changes when closing documents • Close windows when quitting an application • Prefer tabs when opening documents</sup>

<br>

[Desktop & Dock › Mission Contorl](https://www.icloud.com/shortcuts/30d6a3e2fcfc4753971edcf9bf8631cd) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change one or more “Mission Control” settings (Desktop & Dock › Mission Control)<p><sup>__Parameters__<br>Automatically rearrange Spaces based on most recent use • Displays have separate Spaces • Drag windows to top of screen to enter Mission Control • Group windows by application • When switching to an application, switch to a Space with open windows for the application</sup>

<br>

[Displays › Automatically Adjust Brightness](https://www.icloud.com/shortcuts/142abd3279bf4c26b5caa18c4f43341b) ${\sf\small\color{DeepSkyBlue} macOS}$<br><sub>_The toggle won’t reflect the changed state until System Settings is restarted_</sub><p>Toggle “Automatically adjust brightness” (Displays)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Menu Bar › Automatically Hide And Show The Menu Bar](https://www.icloud.com/shortcuts/16c6bfc7fcb14ef889a0a73c71423816) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change “Automatically hide and show the menu bar” (Menu Bar)<p><sup>__Parameters__<br>Always • On Desktop Only • In Full Screen Only • Never</sup>

<br>

[Menu Bar › Show Menu Bar Background](https://www.icloud.com/shortcuts/4b013a82a9ba49fda5f579d91341c7fb) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change “Show menu bar background” (Menu Bar)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Menu Bar › Clock](https://www.icloud.com/shortcuts/ec220408957b47ab9ad46a6d26f5d493) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change one or more Clock settings (Menu Bar › Menu Bar Controls)<p><sup>__Parameters__<br>Announce the time • Style • Flash the time separators • Show AM/PM • Show date • Show the day of the week • Display the time with seconds • Interval</sup>

<br>

[Menu Bar › Show Battery Percentage](https://www.icloud.com/shortcuts/25fbc990cd244b5ebdf9bbee14bab7af) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Show Percentage” (Menu Bar › Menu Bar Comtrols › Battery › Options)<p><sup>__Parameters__<br>Off • On • Toggle</sup>

<br>

[Menu Bar › Fast User Switching](https://www.icloud.com/shortcuts/7f8b7313b3be4f34bf8683bbaa865c2f) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change “Fast User Switching” (Menu Bar › Menu Bar Comtrols)<p><sup>__Parameters__<br>Full Name • Account Name • Icon</sup>

<br>

[Notifications › Notification Center](https://www.icloud.com/shortcuts/c578638d141a425f89fa9bf144474c4c) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change one or more Notification Center settings (Notifications › Notification Center)<p><sup>__Parameters__<br>Allow notifications when the screen is locked • Allow notifications when mirroring or sharing the display • Allow notifications when the display is sleeping • Show previews • Summarize notifications</sup>

<br>

[Notifications › Application Notifications](https://www.icloud.com/shortcuts/1f9c0e6c26ed4b3ba2833f5c7042e30b) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change one or more notification settings for a specific application (Notifications › Application Notifications)<p><sup>__Parameters__<br>Alert style • Critical notifications • Allow notifications • Time sensitive notifications • Badge application icon • Notification grouping • Play sound for notification • Show in Notification Center • Show notifications on lock screen • Show previews</sup>

<br>

[Sound › Play User Interface Sound Effects](https://www.icloud.com/shortcuts/01f69b58ce0c4bf1a47ffd7bf79af2df) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Play user interface sound effects” (Sound › Sound Effects)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Sound › Play Feedback When Volume Is Changed](https://www.icloud.com/shortcuts/29c18f5b9b194cbf91543b860443609f) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Play feedback when volume is changed” (Sound › Sound Effects)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Sound › Play Sound On Startup](https://www.icloud.com/shortcuts/e34d752371b644e08e4e66b8846957b0) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Play sound on startup” (Sound › Sound Effects)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Trackpad › Tracking Speed](https://www.icloud.com/shortcuts/ccd1705b6c2a4999aa81a30b1e228eb0) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change “Tracking speed” (Trackpad › Point & Click)<p><sup>__Parameters__<br>`0.0` • `0.125` • `0.5` • `0.6875` • `0.875` • `1.0` • `1.5` • `2.0` • `2.5` • `3.0`</sup>

<br>

[Trackpad › Click Pressure](https://www.icloud.com/shortcuts/d933ee204a384e19962c7a8e9dcb2337) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change “Click” (Trackpad › Point & Click)<p><sup>__Parameters__<br>Light • Medium • Firm</sup>

<br>

[Trackpad › Force Click And Haptic Feedback](https://www.icloud.com/shortcuts/65e95291b1c04e0897fe23defbc784a6) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Force Click and haptic feedback” (Trackpad › Point & Click)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Trackpad › Look Up & Data Detectors](https://www.icloud.com/shortcuts/32c3f02492c74f13a11a7df765e2132e) ${\sf\small\color{DeepSkyBlue} macOS}$<br><sub>_Wrongly called “Force Click and haptic feedback” in the action_</sub><p>Change “Look up & data detectors” (Trackpad › Point & Click)<p><sup>__Parameters__<br>Off • Force Click with One Finger • Tap with Three Fingers</sup>

<br>

[Trackpad › Secondary Click](https://www.icloud.com/shortcuts/5db14aa8c7ec46c79b503fa348ff48d1) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change “Secondary click” (Trackpad › Point & Click)<p><sup>__Parameters__<br>Off • Click with Two Fingers • Click in Bottom Right Corner • Click in Bottom Left Corner</sup>

<br>

[Trackpad › Tap To Click](https://www.icloud.com/shortcuts/e31537fdbd4b4047b8a0315affe3bfb8) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Tap to click” (Trackpad › Point & Click)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Trackpad › Natural Scrolling](https://www.icloud.com/shortcuts/3090805fb7514726928df7d4eac59c05) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Natural Scrolling” (Trackpad › Scroll & Zoom)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Trackpad › Zoom In Or Out](https://www.icloud.com/shortcuts/fe8a470135694186b1c1bf21911333b3) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Zoom in or out” (Trackpad › Scroll & Zoom)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Trackpad › Smart Zoom](https://www.icloud.com/shortcuts/983acd1dca2d4cb59368cdf44f431dc9) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Smart zoom” (Trackpad › Scroll & Zoom)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Trackpad › Rotate](https://www.icloud.com/shortcuts/7c7f2a060caa47359d6da959321cf495) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Rotate” (Trackpad › Scroll & Zoom)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Trackpad › Swipe Between Pages](https://www.icloud.com/shortcuts/68f1446300c0442593da362f77d7429c) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change “Swipe between pages” (Trackpad › More Gestures)<p><sup>__Parameters__<br>Off • Swipe Left or Right with One Finger • Swipe with Two Fingers • Swipe with One or Two Fingers</sup>

<br>

[Trackpad › Swipe Between Full-Screen Applications](https://www.icloud.com/shortcuts/3ec27345793e4a708a443aabee9434e1) ${\sf\small\color{DeepSkyBlue} macOS}$<br><sub>_Wrongly called “Swipe between pages” in the action_</sub><p>Change “Swipe between full-screen applications” (Trackpad › More Gestures)<p><sup>__Parameters__<br>Off • Swipe Left or Right with Three Fingers • Swipe Left or Right with Four Fingers</sup>

<br>

[Trackpad › Notification Center Gesture](https://www.icloud.com/shortcuts/50f67a1cd28541cabaef6f7fe23d6611) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Toggle “Notification Center” (Trackpad › More Gestures)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>

[Trackpad › Mission Control Gesture](https://www.icloud.com/shortcuts/42dcb8713fde485486d2de0a44719758) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change “Mission Control” (Trackpad › More Gestures)<p><sup>__Parameters__<br>Off • Swipe Up with Three Fingers • Swipe Up with Four Fingers</sup>

<br>

[Trackpad › App Exposé Gesture](https://www.icloud.com/shortcuts/65a7d64f87f44c69b2ec85d61f1527f1) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Change “App Exposé” (Trackpad › More Gestures)<p><sup>__Parameters__<br>Off • Swipe Down with Three Fingers • Swipe Down with Four Fingers</sup>

<br>

[Trackpad › Show Desktop Gesture](https://www.icloud.com/shortcuts/bd818fb595e9468ab3655bb3bfdeb6c9) ${\sf\small\color{DeepSkyBlue} macOS}$<br><sub>_The toggle won’t reflect the changed state until System Settings is restarted_</sub><p>Toggle “Show Desktop” (Trackpad › More Gestures)<p><sup>__Parameters__<br>Turn Off • Turn On • Toggle</sup>

<br>
<br>

> __Safari__
###
[Clear History](https://www.icloud.com/shortcuts/fbf7dc393a4f44479da72291b7504f62) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Opens the “Clear History” dialog in Safari<p><sup>__Parameters__<br>Last Hour • Today • Today and Yesterday • All History</sup>

<br>

[Open View](https://www.icloud.com/shortcuts/3d900f08e71e46da92513ef276025e09) $\sf\small\color{DeepSkyBlue}\(hidden\ on\ macOS\ only\)$<p>Opens the given View in Safari<p><sup>__Parameters__<br>Bookmarks • History • Reading List • Start Page • Tab Overview • Default Tab Group • Private Tab Group • Sidebar • Shared with You</sup>

<br>

[Close View](https://www.icloud.com/shortcuts/66b3186530fd492eaa4808c1f5cf3931)<p>Opens Safari and closes the given View<p><sup>__Parameters__<br>Bookmarks • History • Reading List • Start Page • Tab Overview • Sidebar • Shared with You</sup>

<br>

[Bookmark Current Page](https://www.icloud.com/shortcuts/03fd3d58b356445dbd2b60362302e922)<p>Opens the “Add Bookmark” dialog for the current Safari web page<p><sup>__Options__<br>Title</sup>

<br>

[Bookmark URL](https://www.icloud.com/shortcuts/0a32178abc4248c1bbb034f8aca55696)<p>Silently adds the given URL with optional name to the end of the root Safari “Bookmarks” folder<p><sup>__Options__<br>Name</sup>

<br>

[Find Bookmarks](https://www.icloud.com/shortcuts/f1bac8b295be482bbca14f6be591ff84) $\sf\small\color{DeepSkyBlue}\(hidden\ on\ macOS\ only\)$<p>Finds Safari bookmarks<p><sup>__Options__<br>Add Filter • Sort by • Limit</sup><br>

<br>

[Open Bookmark](https://www.icloud.com/shortcuts/656c86427f9d435fb416bd287f207c4b) $\sf\small\color{DeepSkyBlue}\(hidden\ on\ macOS\ only\)$<p>Opens the given bookmark in a new tab in the current tab group

<br>

[Delete Bookmarks](https://www.icloud.com/shortcuts/8f645d98155b4f469e27ef782c440b9b)<p>Delete one or more Safari bookmarks – use in combination with the Find Bookmarks action

<br>

[Open URL/Create Tab in Current Tab Group](https://www.icloud.com/shortcuts/781a72027b634c8c8963b6aad2a38dd6)<br><sub>_Actual title: “Create Tab for URL“_</sub><p>Opens an optional URL or a blank tab – in the current tab group – unlike any of the official actions<p><sup>__Options__<br>URL</sup>

<br>

[Create New Tab](https://www.icloud.com/shortcuts/65a7ba0a4cb54084a46744c4948407b3) $\sf\small\color{DeepSkyBlue}\(hidden\ on\ macOS\ only\)$<p>Opens Safari and creates a new blank tab – in the current tab group on macOS – in the default tab group on iOS

<br>

[Find Tabs](https://www.icloud.com/shortcuts/ce0ec1db3e7a4d60928af67ad6e21f2c) $\sf\small\color{DeepSkyBlue}\(hidden\ on\ macOS\ only\)$<p>Finds Safari tabs – doesn't work in the Private Tab Group<p><sup>__Options__<br>Add Filter • Sort by • Limit</sup><br>

<br>

[Search Tabs](https://www.icloud.com/shortcuts/33017293f6c04ec798cd73f1dca2a16f)<p>Opens Safari and searches for tabs in the current tab group's Tab Overview<p><sup>__Parameters__<br>Keyword</sup>

<br>

[Switch Tab](https://www.icloud.com/shortcuts/79960341e47a40c7a7246bc2a0f45280) $\sf\small\color{DeepSkyBlue}\(hidden\ on\ macOS\ only\)$<p>Opens Safari and switches to the given tab<p><sup>__Parameters__<br>Tab</sup>

<br>

[Close Tab](https://www.icloud.com/shortcuts/8b07de524c214f859a32366905b9cc32) $\sf\small\color{DeepSkyBlue}\(hidden\ on\ macOS\ only\)$<p>Opens Safari and closes the given tab<p><sup>__Parameters__<br>Tab</sup>

<br>

[Open Tab Group](https://www.icloud.com/shortcuts/a03c00999a574a8a9c0a78b92aa6282f) $\sf\small\color{DeepSkyBlue}\(hidden\ on\ macOS\ only\)$<p>Opens the given tab group in Safari<p><sup>__Parameters__<br>Tab Group</sup>

<br>

[Create Tab Group](https://www.icloud.com/shortcuts/45a42efecf8f4c03b6de081e6a7667b8) $\sf\small\color{DeepSkyBlue}\(hidden\ on\ macOS\ only\)$<p>Opens Safari and creates a new tab group with the given name (or “Untitled” if no name is given)<p><sup>__Options__<br>Tab Group Name</sup>

<br>

[Find Tab Groups](https://www.icloud.com/shortcuts/675a0799c41943fe85ecb51bb3984e7d) $\sf\small\color{DeepSkyBlue}\(hidden\ on\ macOS\ only\)$<p>Finds Safari tab groups<p><sup>__Options__<br>Add Filter • Sort by • Limit</sup><br>

<br>
<br>

> __Miscellaneous__
###
[Change Shortcut Attribute](https://www.icloud.com/shortcuts/391372497e7c425a90b92bb6bafbacf7)<p>Change one of the attributes of a specific shortcut<p><sup>__Parameters__<br>Receive Input From Spotlight • Show in Share Sheet • Show on Apple Watch • Pin in Menu Bar • Receive What’s On Screen • Use as Quick Action • Allow Running When Locked</sup><br><sub>__Options__<br>Open When Run</sub>

<br>

[Get Details of Shortcut](https://www.icloud.com/shortcuts/770cfe1d75b246b5adae1da01ea8b550)<p>Get a specific detail about one or more shortcuts – use in combination with the Get My Shortcuts and Filter Files actions<p><sup>__Parameters__<br>Folder • Icon • Action Count • File Size • File Extension • Date Created • Last Modified Date • Name</sup>

<br>

[Installed Apps Settings URLs](https://www.icloud.com/shortcuts/00b53bd9ab7b49e1b4b568d6f2faa9fd) ${\sf\small\color{DeepSkyBlue} iOS}$<br><sub>_Use with e.g. Open URL or Get URLs from Input_</sub><p>Get the settings URL scheme for every app installed<p><sup>__Options__<br>Limit</sup>

<br>

[Lock App](https://www.icloud.com/shortcuts/7fa46ae5058c4d069928c7e06596b3b3) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Changes whether the selected application is locked. Locked apps require authentication to access.<p><sup>__Parameters__<br>Lock • Unlock • Toggle</sup>

<br>

[Mission Control](https://www.icloud.com/shortcuts/e428567e72b444cf85f2b10e143a43b0) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Open Mission Control

<br>

[App Exposé](https://www.icloud.com/shortcuts/5522317ec06848f1a2b8ae727c49c60d) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Open App Exposé

<br>

[Show Desktop](https://www.icloud.com/shortcuts/21af2ce93344418f8b3345a4509a7ffe) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Show Desktop

<br>

[Delete Contact](https://www.icloud.com/shortcuts/f66e6cccfb0f4cebb9aca0d4da3f4a2f)<p>Deletes one or more contacts<p><sup>__Parameters__<br>Contact</sup>

<br>

[Find Focus](https://www.icloud.com/shortcuts/71375f2726c140beb4352ba9653479fd) ${\sf\small\color{DeepSkyBlue} iOS}$<p>Get a list of all Focus modes<p><sup>__Options__<br>Limit</sup>

<br>

[Family Member Details](https://www.icloud.com/shortcuts/6a578a3c9e054f8d8d4d2afcf5fc79cf)<p>Open the details page for a specific member in (System) Settings › Family

<br>

[Get Details of Shazam](https://www.icloud.com/shortcuts/a78bed33f41047f9ae4010cb4e73f43b)<p>Gets a specific piece of information from the Shazam media passed into the action<p><sup>__Parameters__<br>Apple Music ID • Artist • Title • Is Explicit • Lyrics Snippet • Lyrics Snippet Synced • Artwork • Video URL • Shazam URL • Apple Music URL • Name</sup>

<br>

[Get Details of Ride Status](https://www.icloud.com/shortcuts/39d199f8ed834574be0cfa7a93ca0c1e)<p>Gets a specific piece of information from the ride statuses passed into the action<p><sup>__Parameters__<br>Vehicle Information • Drop Off Time • Pickup Time • Pickup Location • Drop Off Location • Minimum Price • Maximum Price • Ride Option Name • Driver • Name</sup>

<br>

[Get Firewall State](https://www.icloud.com/shortcuts/5f3227380135451d873feb9afa00436a) ${\sf\small\color{DeepSkyBlue} macOS}$<p>Get the current Firewall policy

<br>
<br>

> __Third Party Services__
###
[Add to Pinboard](https://www.icloud.com/shortcuts/018a1ed6474448f1a40ad90795952804)<p>Adds the URL passed into the action to your Pinboard – requires access to your Pinboard account<p>

<br>

[Get Pinboard Bookmarks](https://www.icloud.com/shortcuts/c77470ba888c4f11bb90369b7d94663b)<p>Gets bookmarks in your Pinboard account – requires access to your Pinboard account<p>

<br>

[Upload to Imgur](https://www.icloud.com/shortcuts/be15bed49b5c4b9393548d7d8fa38168)<p>Uploads the input to Imgur<p><sup>__Options__<br>Upload Anonymously • Direct Link • Create Album • Title • Description</sup>

<br>

[Post to WordPress](https://www.icloud.com/shortcuts/4fcf8fafba874096b36b888d8e3a9097)<p>Posts the input to a WordPress blog as a new post or page – requires access to your WordPress account<p>

<br>

[Post to Tumblr](https://www.icloud.com/shortcuts/b61947a637a94192b120158a695f20d2)<p>Posts the content passed into the action to Tumblr – requires access to your Tumblr account<p>

<br>
<br>
