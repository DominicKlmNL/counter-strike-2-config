<div align="center">
  
# Counter-strike 2 Configuration Files

</div>
<br>

<div id="logo" align="center">

  ![Apex Legends](./assets/CS2-icon.png)

</div>
<br>

<div id="navigation" align="center">

| - [Introduction](#introduction) - | - [Context](#Context) - | - [Files](#Files) - | - [Installation](#Installation) - | - [Launch options](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/launchoptions.md) - | - [In-game settings](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/ingame.md) - |  
| - [Autoexec.cfg](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/autoexec.cfg) - | - [Nvidia settings](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/nvidia-settings.md) - | - [Keybind scancode guide](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/KeybindScancodeGuide.md) - | - [Changelog](#CHANGELOG) - | - [License](#License) - |

</div>
<br>

<div id="introduction">

## Introduction

All settings in the configuration file, launch options and autoexec have been validated.</p>
In the instructions for launch options there is a table with the function and benefit of the command.</p>
For the autoexec.cfg the function can be found as comments behind the setting within the file. </p>
<br>

</div>

<div id="qualitycontrol" align="justified">

# Quality Control on configurations

<b> Latest validation:</b> 2026-09-03 ✅  
<b> Frequency of validation:</b> Periodically  
<b> Results latest validation:</b> 0 commands changed  
<b> Registered:</b> 0 commands have been added ✅

</div>
<br>

<div id="Context">

# Context

This repo contains multiple files that can be used to improve the stability and performance for Counter-strike 2, it has been created over a number of years by collecting and trying possibilities. For some, there might be no new settings and for others it might be exactly what they were missing.</p>

This configuration has been created using my own rig, please keep in mind that you should make sure it is compatible with your pc. 

If you are unsure whether settings are fit for your machine and/or you are experiencing unexpected stability issues, feel free to discuss on this repository in the [discussions](https://github.com/DominicKlmNL/counter-strike-2-config/discussions) section. I will try to help as much as I can. </p>
<br>

| Component | Type | Note |
| --- | :--- | :--- |
| CPU | AMD Ryzen 9 3900X | |
| GPU | MSI Geforce RTX 3060 | 12GB |
| Motherboard | Asrock B550 Phantom Gaming 4 | AM4 Socket |
| Memory(RAM) | Corsair Vengeance LPX | 64GB 3600-18 DDR4 |
| Mouse | Keychron M3-A1 Wireless | 1000hz 2.4Ghz |
| Keyboard | Keychron K10 Max | G-mode / Cabled |
| Headset | HyperX Cloud Alpha Wireless | |

</div>
<br>

<div id="Files">

# Files
<br>

| File | Purpose |
| --- | :--- |
| [Launch options](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/launchoptions.md) | A number of commands that can be used as launch options in Steam, to start Counter-strike 2 with additional configuration |
| [In-game settings](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/ingame.md) | All the Display and Advanced Video in-game settings for Counter-strike 2 optimized with these supporting config files |
| [autoexec.cfg](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/autoexec.cfg) | Configuration file that can be loaded into Counter-strike 2 when starting the game |
| [Nvidia settings](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/nvidia-settings.md) | Settings for Nvidia Control Panel, that will help to optimize your game beyond just the game |
| [Keybind scancode guide](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/keybind-scancode-guide.md) | A quick overview guide that shows all the scancodes required for your CS2 keybinds |

<br>
</div>

<div id="Installation">

# Installation
Download the files from [here](https://github.com/DominicKlmNL/counter-strike-2-config/archive/refs/heads/main.zip), extract the files from the ZIP onto your machine. Each file requires a different location, so per file an instruction is available.

<br>

# Launch options

Follow the extended instructions on the [Steam Counter-strike 2 Launch options](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/launchoptions.md) page.

<br>

# Counter-strike 2 In-game settings

Follow the extended instructions on the [Counter-strike 2 in-game settings](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/ingame.md) page.

</div>
<br>

# Autoexec.cfg

> [!WARNING]
> Make sure there is no existing autoexec.cfg or make sure to backup the old file and rename it.
> The autoexec contains a number of keybinds, make sure to customize or disable them 

1. Copy the [autoexec.cfg](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/autoexec.cfg) from the folder where you extracted the files
2. Open Steam and go to your Library tab
3. Right+click Counter-strike 2 and go to <b>Manage</b> in the dropdown and click <b>"Browse Local Files"</b>
4. This will open your Counter-strike 2 installed folder, open the following folders -> <b>*game*</b> -> <b>*csgo*</b> -> <b>*cfg*</b>
5. Paste the <b>autoexec.cfg</b> file in the <b>C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg</b> or if you installed it on another drive in the corresponding map <b>X:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg</b>
<br>

# NVIDIA settings

> [!CAUTION]
> These settings only work on computers with NVIDIA videocards and use the NVIDIA Control Panel to configure the videocard.

Follow the extended instructions on the [Nvidia Settings](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/nvidia-settings.md) page.

<p> $\color{blue}\textsf{NOTE}$ Currently not working on AMD settings, but if I get the chance this might be added. </p>
<br>

# Keybind Scancode Guide

> [!TIP]
> Use this guide to easily set up Counter-strike 2 binds in line with the required Scancodes

Since the arrival of CS2 it is no longer possible to use the old binds, as its replacement we now have to bind it through scancodes (e.g. bind scancodeXX "Command"). </p>
This overview serves as a quick reference sheet that has the scancodes mapped out and is easy to access. </p>

Check out the Keybind Scancode Guide on the [Keybind scancode guide](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/keybind-scancode-guide.md) page.

<br>

<div id="CHANGELOG" align="left">

# CHANGELOG

For the version history and changelog, see [changelog](./docs/CHANGELOG.md) file for details. </p>
Changes to README or LICENSE are not added each time, as they server as a guideline and instruction. </P>

</div>
<br>

<div id="License" align="left">

# License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

</div>
<br>

<div align="center">
<br>

[Back to Top](#Top)

</div>
