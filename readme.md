# EK Switch Hitter Layouts

## About
These are optional layouts set to test out keyboards that aren't supported directly by [EliteKeyboards](http://elitekeyboards.com/) [Switch Hitter](http://elitekeyboards.com/switchhitter.php) tool. I had to implement some workarounds, as EK's software is a bit finicky.
Namely:

- LCtrl inexplicably doesn't work on some layouts, but every other keys work fine. To remedy this, you can simply switch to a standard one and it seems to work fine. The Keyboard layouts affected are:
	- IBM Model F AT (ANSI)
	- IBM Model F AT (Stock)
	- IBM Model F XT
	- Leopold FC660M/C
	- Planck 40% (Default)
	- Vortex Poker II & Pok3r

- Keys that are used on a hardware level (ie FN/PN, or any number of layer switching) do not send scancodes, that's just how they work. They are instead replaced with blank space.

- Keys larger than 2 units in height are not allowed. This only affects the Model F XT, which uses a long num+.

## Setup
1. Click "Clone or Download" and "Download Zip."
2. Unzip folder, inside you should see a series of .kbl files.
3. Navigate to C:\Users\YourNameHere\AppData\Roaming\EliteKeyboards\Layout and copy the .kbl files you want.
4. If open, restart the Switch Hitter utility.