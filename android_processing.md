# Setting Up Processing with Android Mode 
Issue| Solution / Comment
---|---
The Android emulator will not run properly from a USB or network share.|This is due to the lack of processor support software for the Emulator being installed on the machines. This is also why admin access is needed for the install. Each computer should install download the emulator software independently (sigh)
As of Dec 9 2020, Processing 4.1.1 has a bug where it does not list the available modes if selected from the Mode selection drop down.|A solution has been found to select either the tools or to go to sketch ==> import library  