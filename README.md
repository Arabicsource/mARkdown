# mARkdown :: a scheme for tagging historical texts in Arabic

The detailed description of the sceme can be found at [my website](http://maximromanov.github.io/mARkdown/)

## EditPad Pro Highlighting & Navigation Schemes

### 1. Installation/Settings

#### Windows:

- Copy all files from “DropBox/EditPadPro” to “%APPDATA%\JGsoft\EditPad Pro 7” on your computer. Copy-paste the path between quotation marks into Explorer, hit Enter and you will get to the folder that you need. [Re]start EditPad Pro and open any geographical text.

- IMPORTANT: For highlighting/markdown scheme to work the file must have no extension (i.e., instead of Filename.txt it must be just Filename), and begin with the following string “#####SUBJECT#GEOGRAPHY#”. If you just added this string, the highlighting scheme will not work automatically, you will need to restart EditPadPro, or refresh settings: Options > Configure File Types… > Tab: Colors and Syntax > Click “Refresh” > Close “Configure File Types” Window.
Now the text file must show colored highlights (test this on JK_000413)
The highlighting scheme is work in progress. I will be notifying you if/when you need to update settings (essentially, repeat the copy-paste)

#### Linux (Ubuntu)

- Install Wine (https://www.winehq.org) to run the Windows version of EditPad Pro. Then, save the installation file for EditPad Pro. Open the terminal, cd to your download directory, and enter: wine SetupFileName.exe or wine SetupFileName.exe /32 (to force a 32-bit install), or open the downloaded file with Wine through open with…, to install EditPad Pro. Double-click the EditPad Pro icon that the installer placed on your desktop to start EditPad Pro. If there's no desktop shortcut, type wine "c:\Program Files\Just Great Software\EditPadPro7\EditPadPro7.exe" in terminal (assuming you used the default installation folder).

- The other steps should be taken exactly as described for Windows version. Just consider the path that you need to copy the setting files is located in     /home/USER_NAME/.wine/drive_c/users/USER_NAME/Application Data/JGsoft/EditPad Pro 7.
This might work for other versions of the Linux, but you need to make sure about the abovementioned file path.

#### Mac

- EditPad Pro is a Windows software, but it can be used on Mac with some kind of virtualization option (Parallels, Fusion, Virtual Box—the first two are commercial, but more stable). The Mac option is quite costly, since it also requires a licensed version of Windows (7 and higher—I would highly recommend Professional, Enterprise, or Ultimate versions of Windows for stability).

- Then, follow the instructions for Windows above. 
