# Chocolate Quake // WinQuake VS2019-22
Modification of the Visual Studio 2015 Build of Quake originally done by Philip Buuck.

Project was rebuilt using Visual Studio 2019 and 2022. This compile was done on a PC using the full set of C++ tool packages available from Visual Studio, though the only *required* package is the default "Desktop Development with C++" workload. Once the repo has been downloaded or cloned, the Visual Studio Solution can be found in the WinQuake\HandmadeQuake folder. 

A note on compiling: Visual Studio from 2015 onward will attempt to build in x64 mode by default, but set up to build must be done in x86 mode (or Win32 for previous versions of Visual Studio). At the top of the Visual Studio window, if you see x64 in a drop down box, change it to x86 or Win32, whichever your version uses. Then build, and everything should compile. This build has not been tested with a disk drive and the original Quake CD.

*After* compiling the solution from the WinQuake/HandmadeQuake folder; if you wish to patch the game to play the soundtrack, my recommended download can be found here: https://www.moddb.com/games/quake/addons/glquake-winquake-ogg-playback . You can also look online for other solutions to add audio, or pop in the Quake CD if you own a copy and give that a shot!

Unfortunately, the original videos that Philip did seems to have been removed from youtube, but I was able to find a compiled list of most of the series. I am going to see about something relatively painless like a google drive or dropbox link to access the VODS since they are too large to upload to GitHub.

Final notes, this repo does not contain any .pak files, those must be obtained independently. Your best bet for a free option would be to obtain the Episode 1 Shareware, which is freely available online. Once the project has been built, inside of the WinQuake\HandmadeQuake folder, a new folder called Debug will show up. Inside of that folder is the HandmadeQuake exe. Lastly, it should be said that this is not meant to be an advanced source port, but rather a learning tool for building and compling your own version of the original software. In particular, to learn without the snags and pitfalls that the original code brings today. 

Released with thanks & acknlowledgement to Philip Buuck for the original project and to ID Software for creating Quake in the 90s.

ChotoTheBright - July 2024
