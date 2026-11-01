# Project Classic22
**Project Classic22** converts the Android version of _Rovio Classics: Angry Birds_ into a game that runs on Windows.

## Requirements
1. Windows 10 or 11.
2. A x86_64 APK of _Rovio Classics: Angry Birds_.
3. A graphics card that supports Vulkan.

## Installing
1. Get an APK of the latest version of Rovio Classics: Angry Birds, x86_64 architecture. This could be acquired if you bought the game before it was removed from the Google Play Store, in addition to extracting it using tools like [SAI](https://github.com/aefyr/SAI). Make sure to merge the APK afterwards.
2. Download  `ProjectClassic22.exe` from [Releases](https://github.com/brilolo5/ProjectClassic22/releases), open it and select the APK.
3. The tool runs automatically and converts the game to a Windows executable. It also installs [MelonLoader](https://github.com/aefyr/SAI), along with several patches that require the game to run.

## Mod support
[MelonLoader](https://github.com/aefyr/SAI) is installed by default, mods go in the `Mods` folder. Don't delete `GamePatches.dll` from there: the game won't load without it.

A small modding API is also included.
