# Carillon-AppleALC-Version
#### This is a Fork of [nicoSWD / Carillon](https://github.com/nicoSWD/Carillon)

## Hackintosh Chime Boot Sound
## Working for macOS Sierra 10.12 to macOS Sequoia 15

### This version of Carillon is specifically for User with AppleALC.kext


*Carillon* is an open source OS X app, specifically for Hackintosh machines, that plays the classic "Chime" boot sound on startup that real Macs have.

A new launch daemon will be added that triggers the sound, meaning, unlike most similar apps, this one runs much earlier during the boot process, even before the login screen appears.
No crappy AppleScript solution that triggers when you're already on the Desktop, no outdated PrefPane

It has currently been tested on macOS 11, 12, 13, 14,15 macOS 10.15 macOS 10.14, macOS 10.13 and macOS 10.12, but it should work on previous and future versions as well. Please [report](https://github.com/chris1111/Carillon-AppleALC-Version/issues/new) any issues you may have.

No new icons or settings will be added. Reboot your system to enjoy.

![Screenshot](https://user-images.githubusercontent.com/6248794/204088035-a96b288c-94f9-422b-ab41-e779ae1046b3.png)

You need Xcode and the Command Line tools

##### Usage: Download or clone Carillon-AppleALC-Version-master (You need Xcode)
- To compile the binary file and create the package, double-click on the `Builder` file 

##### Usage BUILD

`cd ~/`

`git clone https://github.com/chris1111/Carillon-AppleALC-Version.git`

`~/Carillon-AppleALC-Version/BUILDER`


##### Usage: Rebuild the Package
- After compiling, you can recreate the package any time by double-clicking on the `Packager` file

##### Usage: Uninstall Carillon
- Double-clicking on the `Uninstall-Carillon.command` file

- You can change the description in the Welcome in background / Welcome; same thing with the Background file, you can change it.

###  **ALTERNATIVE VERSION**

- I added a alternative release for macOS 10.14, macOS 10.13 and macOS 10.12 , which uses a different approach to play the audio. If you're having troubles with the original version.
[Download ➤ v1 Carillon (Alternative)  ](https://github.com/chris1111/Carillon-AppleALC-Version/releases)

![Modular Image Creation](https://i62.servimg.com/u/f62/18/50/18/69/captu330.png)

