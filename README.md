# Croatian-US-windows

Croatian US keyboard (CroUS) keyboard layout for Windows operating systems.

This is standard US keyboard layout where you get Croatian characters or layout by pressing AltGR (right Alt) key.
In Linux, this keyboard is known as hr-US (in X11) or crous (in console).
In short, developers like it.

Keyboard layout for different operating systems:
* [Croatian-US-linux](https://github.com/kost/Croatian-US-linux)
* [Croatian-US-windows](https://github.com/kost/Croatian-US-windows)
* [Croatian-US-mac](https://github.com/kost/Croatian-US-mac)

## Installation

Extract ZIP from releases page. Run setup.exe.

You can choose Croatian US keyboard layout from Input Language Control panel entry.

*Note*: Sometimes AltGr combination does not work out of the box. You have to press Ctrl+Alt+some-croatian-letter in order
to push AltGr combination to work. Afterwords, AltGr combination works.

### Step by step installation

Choose "Change keyboards or other input methods" in Control Panel:

![](/doc/control-panel.png)


Choose "Keyboard and Languages" tab and "Change Keyboards" button:

![](/doc/region-and-language.png)


Make sure you have selected Croatian US keyboard:

![](/doc/input-language-crous.png)

## Troubleshooting

*AltGr combination does not work*

Sometimes AltGr combination does not work out of the box. You have to press Ctrl+Alt+some-croatian-letter in order
to push AltGr combination to work. Afterwords, AltGr combination works. Wonderful world of MKLC deployment in short.


*Support for Windows 10?*

"Actually MKLC 1.4 files work fine with Windows 10.  Indeed, language bar disappears, after you change keyboard layout to the custom one. But, once  you log off and and then log on again the language bar re-appears, and everything works great. The only minor nuisance is that there is no preview in language settings, but I can happily live without that :)"
from [Microsoft Answers](https://answers.microsoft.com/en-us/windows/forum/windows_10-hardware/custom-keyboard-layout-with-windows-10/b71c7905-1e30-4b0c-861b-253efd2b5a9e?auth=1)

## Building

You will need to download MKLC:
[Microsoft Keyboard Layout Creator](https://msdn.microsoft.com/en-us/globalization/keyboardlayouts.aspx)

Load up keyboard layout from the src folder and build the keyboard layout packages from MKLC. 


