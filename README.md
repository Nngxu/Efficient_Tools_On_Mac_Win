# Efficient Tools On Mac

## [Karabiner-Elements](https://karabiner-elements.pqrs.org/)

Karabiner-Elements is a keyboard customization tool for macOS. It allows users to remap keys, modify keyboard behavior, and customize shortcuts to tailor their keyboard experience. 

1. Change caps _lock to left _control if pressed with other keys, change caps lock to escape if pressed alone.

	[Asset URL](https://ke-complex-modifications.pqrs.org/#caps_lock_tapped_escape_held_left_control)

2. Change right _command+hjkl to arrow keys

	This asset is in the examples of Complex Modifications.

	![img](./img/right_command.png)

## copyclip

"CopyClip" is a software or app that allows users to manage and enhance their clipboard functionality on computers or mobile devices.

(Download from AppleStore.)


## [MonitorControl](https://github.com/MonitorControl/MonitorControl)

Controls your external display brightness and volume and shows native OSD.

## Others
- Telegram
- Nomachine
- Dropbox
- OBS

# Efficient Tools On Windows

## AutoHotKey

AutoHotKey is a free and open-source scripting language designed for automating various tasks on the Windows operating system. 


1. Change caps_lock to left_control if pressed with other keys, change caps lock to escape if pressed alone.

	URL: https://gist.github.com/sedm0784/4443120

2. Change right_alt+hjkl to arrow keys

```
;About Alt + hjkl for arrow key, refer to: https://www.autohotkey.com/boards/viewtopic.php?t=24521

Hotkey, *k, Off
Hotkey, *h, Off
Hotkey, *j, Off
Hotkey, *l, Off

*RAlt::
    Hotkey, *k, on
    Hotkey, *h, on
    Hotkey, *j, on
    Hotkey, *l, on
return

*RAlt up::
    Hotkey, *k, off
    Hotkey, *h, off
    Hotkey, *j, off
    Hotkey, *l, off
return

*k::send {blind}{up}
*h::send {blind}{left}
*j::send {blind}{down}
*l::send {blind}{right}
```

Usage:
- Create a *.ank file
- Open with Admin

## Others

- CopyQ (Same as CopyClip on Mac)
- ShareX (Screen shot/record)