SC Joystick Mapper V 2.10 - Build 43
(c) Cassini, StandardToaster - 04-January-2015

Contains 9 files:

SCJMapper.exe                The program (V2.10)
SCJMapper.exe.config         Program config (V2.10)              - MUST be in the same folder as the Exe file
SharpDX.DirectInput.dll      Managed DirectInput Assembly        - MUST be in the same folder as the Exe file
SharpDX.dll                  Managed DirectX Assembly            - MUST be in the same folder as the Exe file
OpenTK.dll                   Managed OpenGL Assembly             - MUST be in the same folder as the Exe file
OpenTK.GLControl.dll         Managed OpenGL Assembly             - MUST be in the same folder as the Exe file
Ionic.Zip.Reduced.dll        Managed Zip Assembly                - MUST be in the same folder as the Exe file
log4net.dll                  Managed Logging Assembly            - MUST be in the same folder as the Exe file
log4net.config.OFF           Config file for logging             - To use it - rename as  log4net.config and run the program
                                                                   then look for  trace.log  in the same folder
SCJMapper_QGuide V2.10.pdf    Quick Guide
ReadMe.txt                   This file

graphics folder              Skybox Images                       - graphics folder MUST be in the same folder as the Exe file


Read the Guide first RTFM ;-)
Put all files into one folder and hit SCJMapper.exe to run it

For Updates and information visit:
https://github.com/bm98/SCJMapper-V2/

Scanned for viruses before packing... 
cassini@burri-web.org

Changelog:
V 2.10 - Build 43 - Production
- new feature - added Action Tree context menu for Assign, Clear and Blend
- fix - issue for Js Reassignment if more than one was not yet assigned
- improvement - Right click in Action Tree selects the items (no need to select and then right click anymore)
V 2.10 - BETA Build 41
- fix - issue with null ptr assignment in Device Tuning (review and fix of AC1.0 changes)
- fix - disabled first joystick tab when gamepad is second or later
- improvement - added tooltips for device tabs showing Name and GUID
- improvement - added full 4 number version for beta builds
V 2.10 - BETA Build 40
- rework for AC 1.0
- new feature - add DumpLog to get the AC detected Controller assignments from logfile
- new feature - add Invert checkboxes for supported option items
- new feature - context menu in treeview allows to add/delete action sub items (support addbind mapping in XML)
- update - cannot longer assign cross device mappings (AC 1.0 related - use addbind above)
- update - new options naming and structure (not compatible with pre 2.10 - delete them in the file and then reload)
- update - Profile Version to 1
V 2.8 - BETA Build 37
- new feature - add checkboxes to show Joystick, Gamepad, Kbd and Mapped Only
- fix - Blended ones don't reload with proper visual
V 2.8 - BETA Build 36
- new feature - add invert for single mappings
- improvement - initialization and assignment of Joystick devices
V 2.8 - BETA Build 34
- new feature - add keyboard input
- new feature - add gamepad input as xboxpad
- new feature - add gamepad for tuning 
- new feature - blend single entries with <Space>
- fix - tuning copy to all axis now applies immediately
- improvement - cleanup of some inconsistencies
V 2.7 - Build 33
- fix - if an axis is not mapped the prog will not longer crash (was null ptr exception)
- doc update 2.7
V 2.7 - BETA
- new feature - Joystick Tuning
V 2.6
- fix - taking actionmaps from config file now works
- improvement - added actionmap vehicle_driver
V 2.5
- new feature - support and maintain option tags
- improvement - support and maintain version and ignoreversion attribute / can force ignoreversion="1"
- improvement - makes backup copy before each save (in my documents e.g. layout_my_xyz.xml.backup)
- Update of the Guide for V2.5
V 2.4
- improvement - add new actionmaps for AC 0.9 (flycam, spaceship_turret)
- improvement - supports now assignment of js1 .. js8 - SC may not support all though...
- Update of the Guide for V2.4
V 2.3
- new feature - allow reassignment of the jsN group
- improvement - uniquely identified devices with the same name (use GUID)
- improvement - shows jsN assignment in Joystick tab
- improvement - detection of the SC install path extended to one more Registry entry
- fix - blend unmapped works properly now
- fix - manual entry of SC directory works now
- Update of the Guide for V2.3
V 2.2
- new feature - option to ignore actionmaps in Settings
- improvement - add actionmaps for multiplayer, singleplayer, player
- improvement - GUI layout of Joystick tabs for more than 4 devices
- Update of the Guide for V2.2
V 2.1
- program is maintained at "https://github.com/SCToolsfactory/SCJMapper-V2/releases"
- new feature - option to blend unmapped actions
- improvement - ignore buttons in Settings
- improvement - override the built in detection of the SC folder in Settings
- added - trace log for resolving crash and other issues
- Update of the Guide for V2.1
V 2.0
- program is maintained at "https://github.com/bm98/SCJMapper-V2/releases"
- new feature - get defaultProfile.xml from game assets
- new feature - get actionsmaps from game assets
- new feature - reset to defaults
- new feature - load and save own maps to gamefolders (makes backup in My Documents\SCJMapper)
- new feature - filter the action tree
- new feature - drag and drop an mapping file into the XML window
- new feature - make throttle assignment for any axis
- improved joystick detection (jitter avoidance, limit can be set in Program config file)
- improved button detection (blend buttons that are always on)
- improved sizeable window
- improved settings persist between sessions
- Update of the Guide for V2.0
- removed defaultProfile.xml from distribution (REMOVE IT FROM YOUR FOLDER - else it will be taken as action list)
V 1.4PRE
- using a new Managed DirectX assembly and built with .Net4 (Hope this works for Win8.1)
- added Joystick properties and Axis Names from the Joystick driver
V 1.3
- new feature - read the original defaultProfile.xml from SC to derive the actions (must be in the EXE folder)
- added support for up to 8 devices
- added multibinding i.e. bind the same action to multiple buttons, one for kbd, one for xbox etc. if the profile supports it
- added Dump List - a readable list of the commands (can be saved as txt file - using Save as)
- fixed "Find 1st" 
- Update of the Guide 
- removed MappingVars file from distribution (REMOVE IT FROM YOUR FOLDER - else it will be taken as action list)
V 1.2
- added support for rebinding xboxpad and ps3pad
- added Find 1st  for a Control
- fixed Hat direction not maintained as last Control used
- some GUI refinements
- Update of the Guide (incl MappingVar.csv format)
MappingVar file
- added commands that where missing
- changed from keyboard to xboxpad rebinding where possible to leave kbd intact
V 1.1 
- fixed issue with less than 3 joysticks attached
V 1.0 initial 
