<div  id="header" align="center">

# Counter-strike 2 Keybind Scancode Guide

<br>

</div>

<div id="Navigation" align="center">

[Installation](#Nvidia-settings) | [Settings](#Settings) | [README](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/README.md) | [Launch options](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/launchoptions.md)  |  [In-game settings](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/ingame.md)  |  [Autoexec.cfg](https://github.com/DominicKlmNL/counter-strike-2-configblob/main/autoexec.cfg)  |   [Changelog](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/docs/CHANGELOG.md) | [License](https://github.com/DominicKlmNL/counter-strike-2-config/blob/main/LICENSE)

</div>

<br>

<div id="introduction" align="left">

## Introduction to Counter-strike 2 Keybind's

<br>

When Counter-strike 2 was introduced, one of the first things that was noticed was a recurring problem with keybinds. Suddenly the old method did no longer work. Valve had chosen for a new system, which required most of us to completely rebuild there autoexec and/or other config files. 

Valve introduced the $\color{green}\textsf{Scancode}$, which is based on the $\color{yellow}\textsf{SDL (Simple DirectMedia Layer)}$. SDL translates the physical position of keys into unified virtual scancodes. This was they bypass whatever language layout your operating system is using and talks directly to the physical key switch.

This means that the keys as we know them and have used in binds for all these years, are technically not replaced by a new system. They made it unified across all devices. Regardless, the communication on what that sudden change meant was lacking to say the least. And a lot of us, were clueless on how to fix our configuration files.

To help you be able to quickly figure out which codes you need and the method behind it, we created this guide. The intention is to provide you with a quick reference guide that is simple and easy to understand.

</div>

<br>

<div id="overview" align="left">

## Overview of scancodes

<div id="scancode-1-20" align="left">

##### Scancodes 1-20

<br>

| <sup> 1 </sup> | <sup> 2 </sup> | <sup> 3 </sup> | <sup> 4 </sup> | <sup> 5 </sup> | <sup> 6 </sup> | <sup> 7 </sup> | <sup> 8 </sup> | <sup> 9 </sup> | <sup> 10 </sup> | <sup> 11 </sup> | <sup> 12 </sup> | <sup> 13 </sup> | <sup> 14 </sup> | <sup> 15 </sup> | <sup> 16 </sup> | <sup> 17 </sup> | <sup> 18 </sup> | <sup> 19 </sup> | <sup> 20 </sup> |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| <sup> unused </sup> | <sup> unused </sup> | <sup> unused </sup> | a | b | c | d | e | f | g | h | i | j | k | l | m | n | o | p | q |

</div>

<br>

<div id="scancode-21-40" align="left">

##### Scancodes 21-40

<br>

| <sup> 21 </sup> | <sup> 22 </sup> | <sup> 23 </sup> | <sup> 24 </sup> | <sup> 25 </sup> | <sup> 26 </sup> | <sup> 27 </sup> | <sup> 28 </sup> | <sup> 29 </sup> | <sup> 30 </sup> | <sup> 31 </sup> | <sup> 32 </sup> | <sup> 33 </sup> | <sup> 34 </sup> | <sup> 35 </sup> | <sup> 36 </sup> | <sup> 37 </sup> | <sup> 38 </sup> | <sup> 39 </sup> | <sup> 40 </sup> |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| r | s | t | u | v | w | x | y | z | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 | <sup> ENTER/RETURN </sup> |

</div>

<br>

<div id="scancode-41-60" align="left">

##### Scancodes 41-60

<br>

| <sup> 41 </sup> | <sup> 42 </sup> | <sup> 43 </sup> | <sup> 44 </sup> | <sup> 45 </sup> | <sup> 46 </sup> | <sup> 47 </sup> | <sup> 48 </sup> | <sup> 49 </sup> | <sup> 50 </sup> | <sup> 51 </sup> | <sup> 52 </sup> | <sup> 53 </sup> | <sup> 54 </sup> | <sup> 55 </sup> | <sup> 56 </sup> | <sup> 57 </sup> | <sup> 58 </sup> | <sup> 59 </sup> | <sup> 60 </sup> |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| <sup> ESCAPE </sup> | <sup> BACKSPACE </sup> | <sup> TAB </sup> | <sup> SPACE </sup> | - | <sup> Equals </sup> | <sup> [ </sup> | <sup> ] </sup> | <sup> \ </sup> | <sup> # </sup> | <sup> ; </sup> | <sup> ' </sup> | <sup> ` </sup> | , | . | <sup> / </sup> | <sup> CAPS LOCK </sup> | <sup> F1 </sup> | <sup> F2 </sup> | <sup> F3 </sup> |

</div>

<br>

<div id="scancode-61-75" align="left">

##### Scancodes 61-75

<br>

| <sup> 61 </sup> | <sup> 62 </sup> | <sup> 63 </sup> | <sup> 64 </sup> | <sup> 65 </sup> | <sup> 66 </sup> | <sup> 67 </sup> | <sup> 68 </sup> | <sup> 69 </sup> | <sup> 70 </sup> | <sup> 71 </sup> | <sup> 72 </sup> | <sup> 73 </sup> | <sup> 74 </sup> | <sup> 75 </sup> |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | 
| <sup> F4 </sup> | <sup> F5 </sup> | <sup> F6 </sup> | <sup> F7 </sup> | <sup> F8 </sup> | <sup> F9 </sup> | <sup> F10 </sup> | <sup> F11 </sup> | <sup> F12 </sup> | <sup> Print Screen </sup> | <sup> Scrolllock </sup> | <sup> Pause </sup> | <sup> Insert </sup> | <sup> Home </sup> | <sup> Page Up </sup> |

</div>

<br>

<div id="scancode-76-90" align="left">

##### Scancodes 76-90

<br>

| <sup> 76 </sup> | <sup> 77 </sup> | <sup> 78 </sup> | <sup> 79 </sup> | <sup> 80 </sup> | <sup> 81 </sup> | <sup> 82 </sup> | <sup> 83 </sup> | <sup> 84 </sup> | <sup> 85 </sup> | <sup> 86 </sup> | <sup> 87 </sup> | <sup> 88 </sup> | <sup> 89 </sup> | <sup> 90 </sup> |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| <sup> Delete </sup> | <sup> End </sup> | <sup> Page Down </sup> | <sup> Right </sup> | <sup> Left </sup> | <sup> Down </sup> | <sup> Up </sup> | <sup> Numlock </sup> | <sup> KP / </sup> | <sup> KP * </sup> | <sup> KP - </sup> | <sup> KP + </sup> | <sup> KP ENTER </sup> | <sup> KP 1 </sup> | <sup> KP 2 </sup> |

</div>

<br>

<div id="scancode-91-100" align="left">

##### Scancodes 91-100 + Special

<br>

| <sup> 91 </sup> | <sup> 92 </sup> | <sup> 93 </sup> | <sup> 94 </sup> | <sup> 95 </sup> | <sup> 96 </sup> | <sup> 97 </sup> | <sup> 98 </sup> | <sup> 99 </sup> | <sup> 100 </sup> | <sup>Special</sup> | <sup> 225 </sup> | 
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| <sup> KP 3 </sup> | <sup> KP 4 </sup> | <sup> KP 5 </sup> | <sup> KP 6 </sup> | <sup> KP 7 </sup> | <sup> KP 8 </sup> | <sup> KP 9 </sup> | <sup> KP 0 </sup> | <sup> KP . </sup> |  | <sup> </sup> | <sup> LShift </sup> |

</div>

<br>

</div>
  
<br>

<div id="formatting">

## Formatting keybinds with scancodes

<br>

Now that we have the overview with all the scancodes, we should be able to create the keybinds. But before we dive into the scancodes, let's take a look at the old CS:GO keybinds and compare it to the new system. </p>

<br>

### CS:GO Binds

<br>

To understand a bit more about what changed for binds compared to CS:GO, let's use this example and format it like it was done in CS:GO. </p>

| <sup> Bind </sup> | <sup> Key </sup> | <sup> Command </sup> |
| :---: | :---: | :---: |
| <sup> BIND </sup> | <sup> e </sup> | <sup>  "+use" </sup> |

<br>

	bind e "+use"


The total console command would be like the example above. </p>

<br>

### Counter-strike 2 Binds

### Example 1

Now let's do this same, but this time with the format that is required for Counter-strike 2 </p>

| <sup> Bind </sup> | <sup> Key </sup> | <sup> Command </sup> |
| :---: | :---: | :---: |
| <sup> BIND </sup> | <sup> scancode8 </sup> | <sup>  "+use" </sup> |

<br>

When you take a look at the overview of scancodes, you will notice that $\color{green}\textsf{scancode8}$ corresponds with the key $\color{green}\textsf{e}$ </p>


	bind scancode8 "+use"


The total console command would be like the example above. </p>

<br />

### Example 2

Another example, jump is default bound to the SPACE key. So if we want to translate that bind to Counter-strike 2, you need the following bind sequence. </p>

| <sup> Bind </sup> | <sup> Key </sup> | <sup> Command </sup> |
| :---: | :---: | :---: |
| <sup> BIND </sup> | <sup> scancode44 </sup> | <sup>  "+jump" </sup> |

<br>

Again we can retrace the $\color{green}\textsf{scancode44}$ to the key $\color{green}\textsf{SPACE}$. </p>


	bind scancode44 "+jump"


The total console command would be like the example above. </p>

</div>

<br>

<div id="conclusion" align="left">

## Conclusion

<br>

Although the scancodes sound a bit mysterious and are harder to remember, I hope having this quick reference guide will make it a lot easier to figure out new binds for Counter-strike 2. </p>
And as a little gift after reaching the end of the guide, a little keybind from me for you. Oh and if you wonder what key the scancode64 is. You know where to find it in the overview above and I hope you enjoy the new chat spam bind.</p>

	bind scancode64 "say ¯\_(ツ)_/¯"


</div>

<br>

<div align="center">

<br>

[Back to Top](#Top)

</div>
