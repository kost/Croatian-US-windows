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

Sometimes AltGr combination does not work out of the box. You have to press Ctrl+Alt+some-croatian-letter in order
to push AltGr combination to work. Afterwords, AltGr combination works. Wonderful world of MKLC deployment in short.

## Building

You will need to download MKLC:
[Microsoft Keyboard Layout Creator](https://msdn.microsoft.com/en-us/globalization/keyboardlayouts.aspx)

Load up keyboard layout from the src folder and build the keyboard layout packages from MKLC. 


