<div id="header" align="center">
  
# Counter-strike 2 Launch Options

</div>

<br>

<div id="navigation" align="center">

| - [Introduction](#introduction) - | - [Context](#Context) - | - [Files](#Files) - | - [Installation](#Installation) - | - [Launch options](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/launchoptions.md) - | - [In-game settings](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/ingame.md) - |  
| - [Autoexec.cfg](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/autoexec.cfg) - | - [Nvidia settings](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/nvidia-settings.md) - | - [Keybind scancode guide](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/KeybindScancodeGuide.md) - | - [Changelog](#CHANGELOG) - | - [License](#License) - |

</div>

<br>

<div id="Commands">

## Commands

<p>Before you install the launch options below, it is important that you understand what the commands do and what they mean. All launch options are in the table down below including their function</p>

<br>

| Command | Function | Benefit |
| --- | --- | --- |
| -freq | Forces the game engine to output a video signal at a specific refresh rate. E.g. if you have a monitor with a refresh rate of 180hz, you set the command as ***-freq 180*** | Eliminates screen tearing and ensures the smoothest possible gameplay, provided your monitor supports the refresh rate you set in the command. |
| -fullscreen | Tells your operating system to give the game exclusive control of the display mode, bypassing the desktop window manager. | Minimizes input lag for quicker mouse response and allocates maximum system resources to the game for a potential FPS boost. |
| -console | Automatically opens the developer console as soon as the game launches, allowing you to immediately type commands. | Saves you from having to press a hotkey to open it, allowing you to instantly type configuration commands or check server statuses. It also gives you feedback if you use the autoexec, that it has succesfully been executed. |
  
</div>

<br>

<div id="Launchoptions" align="left">

## Setting things up 🕐


<div id="Install">

##### Expected duration to configure the launch options: $\color{green}\textsf{Approx. 5 min}$

</div>


1. Open Steam and go to your <b>Library</b> tab 
2. Right+click <b>Counter-strike 2</b> 
3. Select <b>"Properties"</b> 
4. Make sure you are on the <b>"General"</b> tab 
5. There is the field called <b>"Launch Options"</b> 
6. Copy the command below and paste it into the <b>Launch Options</b> field, make sure to change the -freq 180 to the corresponding refresh rate for your monitor 


``` 
-freq 180 -console -fullscreen
```


7. Once you pasted the commands in the field, you can close the window and start up Counter-strike 2. The commands will now take immediate effect. 
8. $\color{Green}\textsf{INFO:}$ With the introduction of Counter-strike 2, the game automatically executes the autoexec file if it exists in the CFG folder. Making it unnecessary to add it to the launch options, since the game with execute is regardless.

<br>

</div>

> [!NOTE]
> If you want to start using the autoexec.cfg combined with these commands, make sure to follow the instructions from [README](https://github.com/DominicKlmNL/counter-strike-2-config/edit/main/README.md) on how to install the configuration.

<div align="center">
<br>

[Back to top](#Top)

</div>
