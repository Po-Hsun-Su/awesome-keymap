# awesome-keymap
Keymap for productivity (Linux and Windows).

For example, "CapsLock" plus "i", "j", "k", "l" becomes "↑", "←", "↓", "→".

## Default keymap
Use "CapsLock" as the layer switch. Pressing "CapsLock" + "j" becomes "←" as shown in the layout below.
![default](./keyboard-layout.png)

## Installation
### Windows
1. Install AutoHotkey (https://autohotkey.com/download/)
2. Clone this repo and execute awesome-keymap/windows/caps2fn.exe
3. Put caps2fn.exe to Windows starup folder
(https://support.microsoft.com/en-us/help/4026268/windows-change-startup-apps-in-windows-10)

### Linux

Linux keymap note

xev: key stroke observation program

 configuration is done in /usr/share/X11/xkb

key code -> key symbol -> key event

<TLDE> = 49  is defined in keycodes/evdev

key <TLDE>  is defined in symbols/uscat



Linux:

Modify "symbols/us" to define keymaps

Modify "symbols/pc" to change caps to level 3 shift


setxkbmap -model pc105 -layout us


setxkbmap -model pc104 -layout us



## Uninstall
### Windows
1. Remove caps2fn.exe from Windows starup folder (https://support.microsoft.com/en-us/help/4026268/windows-change-startup-apps-in-windows-10)
