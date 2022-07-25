# WinQuake-VS2019
Modification of the Visual Studio 2015 Build of Quake orig. done by Philip Buuck

Project was rebuilt using Visual Studio 2019. This compile was done on a PC using the full set of C++ tool packages available from Visual Studio 2019, though the only requirements *should* be the "Desktop Development with C++" workload. A note on compiling: Visual Studio from 2015 onward will attempt to build in x64 mode by default, but set up to build must be done in x86 mode (or Win32 for previous versions of Visual Studio). At the top of the Visual Studio window, if you see x64 in a drop down box, change it to x86 or Win32, whichever your version uses. Then build, and everything should compile.

A winmm.dll file is included in the directory, however, _inmm.dll 2.38 will need to be installed on your computer in order to complete the process.
The download can be found here: https://community.pcgamingwiki.com/files/file/107-patched-_inmmdll/

After compiling the solution from the WinQuake/HandmadeQuake folder, the steps to complete the patch can be found here: https://steamcommunity.com/sharedfiles/filedetails/?id=113399618

Final note, this repo does not contain any .pak files, those must be obtained independently.

ChotoTheBright - July 2022
