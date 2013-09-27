UnityDLLExample
===============

Demonstrate the basic setup of .NET DLL (managed assembly) project to be used within Unity project.

This is based on an Unity Forum article "How to build and debug external DLLs" http://forum.unity3d.com/threads/161685-How-to-build-and-debug-external-DLLs


Build a DLL

1) Create an empty Visual Studio solution (.sln) or use an existing solution.
2) Opton the solution
3) File -> Add -> Existing project...
4) Select UnityDLLExample.csproj
5) Build the solution/project
6) The output DLL, UnityDLLExample.dll, will appear in Assets/Plugins folder.

Copy the DLL to your Unity project

1) Create a new Unity project or use an existing one
2) Make sure that there is a folder called "Plugins" under "Assets" folder. If doesn't exist, create one.
3) Copy UnityDLLExample.dll to Assets/Plugins

Use "spin" script, that is compiled into UnityDLLExample.dll

1) Open the Unity project in the Unity
2) Under Project window, navigate to Assets/Plugins folder
3) You should see an icon of UnityDLLExample.dll, with a small "Right arrow" next to it.
4) Click the "Right arrow" to expand the DLL to show the content. You should see a script called "spin"
5) You can drag this script to any object, such as Cube, to make it spin.

Enjoy!

-yoshi
