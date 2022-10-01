# Chocolate Quake -or- WinQuake VS2019
Modification of the Visual Studio 2015 Build of Quake orig. done by Philip Buuck

Project was rebuilt using Visual Studio 2019. This compile was done on a PC using the full set of C++ tool packages available from Visual Studio 2019, though the only requirements *should* be the "Desktop Development with C++" workload. A note on compiling: Visual Studio from 2015 onward will attempt to build in x64 mode by default, but set up to build must be done in x86 mode (or Win32 for previous versions of Visual Studio). At the top of the Visual Studio window, if you see x64 in a drop down box, change it to x86 or Win32, whichever your version uses. Then build, and everything should compile.

This build has not been tested with a disk drive and the original Quake CD. If you wish to patch the game to play the soundtrack, a winmm.dll file has been included in the directory. To complete the process, _inmm.dll 2.38 will need to be installed on your computer. The download can be found here: https://community.pcgamingwiki.com/files/file/107-patched-_inmmdll/

*After* compiling the solution from the WinQuake/HandmadeQuake folder, the steps to complete the patch can be found here: https://steamcommunity.com/sharedfiles/filedetails/?id=113399618

Final notes, this repo does not contain any .pak files, those must be obtained independently. It is also not intended to be an advanced source port, rather a learning tool for building and compling your own version of the original software, without the snags and pitfalls that the original code brings today.

ChotoTheBright - October 2022
