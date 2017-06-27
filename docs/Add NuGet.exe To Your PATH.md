# Check If NuGet.exe Is Already In Your PATH
To check if nuget.exe is already in your system's PATH:
# Open a command prompt.
# Type the following and hit enter: **nuget**
	* If the nuget help documentation is displayed, then nuget.exe is already in your PATH.
	* If you received the message, "'nuget' is not recognized as an internal or external command, operable program or batch file." then nugexe.exe is not in your PATH yet and still needs to be added.

# Add NuGet.exe To Your PATH
If nuget.exe was located on your PC at "C:\My Utilities\nuget.exe", to add nuget.exe to your PATH:
# Open a command prompt.
# Type the following and hit enter: **set PATH=%PATH%;C:\My Utilities**
