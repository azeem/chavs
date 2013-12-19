# Cockos Happy AVS
This is an annotated version of [Cockos Happy AVS](http://visbot.github.io/AVS-Forums/html/t-321482.html).

## Setup
This is a setup that can build the code. It could probably work with different versions.
+ Visual C++ 6.0
+ Windows XP SP3
+ Winamp 5.58

## Build
1. Open workspace vis_avs/vis_Avs.dsw
2. Set Active build configuration to Win32 Release
3. Build vis_chavs.dll (F7). The link settings outputs the dll directly to the winamp plugins directory. Modify in project settings if required.

## Debug
1. Open workspace vis_avs/vis_Avs.dsw
2. Set Active build configuration to Win32 Debug
3. Set winamp executable in project settings
2. Start Debug (F5)

## Nullsoft Advanced Visualization Studio (AVS) v2.0a4 README

Thanks to Paul Holden for the FunkyFX Firewurx APE  

Once you install this baby, fire up Winamp, open up the preferences 
(CTRL+P), go to the Plugins/Visualization section, and select 
Nullsoft AVS as the visualization plug-in. Hit start. 

Once the AVS opens, it will probably be showing a nice black output.
To get AVS to display something more interesting, hit space, or right
click in the black area and select a preset to load.

If you want to create your own presets, click the left mouse button in 
the black area of the window to bring up the AVS Editor window.

The editor lets you create new visuals by adding effects from your Effect
Library (in the upper right) to the Active Effect list (on the left side).
Once you've added effects, you can configure each effect by selecting them
from the Active Effect list. You can also clear the list, or load or save
the list to be loaded later as a preset. 

You can also configure some of AVS's settings by selecting items from the 
Settings section of the Editor. 

Hotkeys for main window:
 *  Any winamp key
 *  R toggles randomswitching
 *  F toggles fullscreen framerate counter
 *  Y and U cycle through presets in order
 *  Space goes to random preset
 *  Enter toggles fullscreen
 *  0,1-9, F1-F10 load presets
 *  Ctrl+above save presets

That's it for now, and enjoy!