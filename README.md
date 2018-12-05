PS3Fw XENON - Located at; https://drive.google.com/open?id=1LXZmbSr5WaTfSXGUIdZ-z6Y0HlZIZwFZ
This is a Custom Firmware for the Playstation 3 that I am working on currently, it is in alpha stage (It is a full CFW but currently 
resides as a CEX only with rogero patterns. It is due to be updated (Will reach v1.00 at least) And, will recieve customisation, hopefully will port Cobra payloads and possible DEX varients as well but all really depends on my time as I am busy a lot of the time, and will be working on PS4 predominently within the console scene!

============================================================================

4.82 V0.11a - Xenon Firmware - By ScriptedArts / OneKubbYT

============================================================================
NEW FEATURE'S; todo

Check out my other work and information
on my work on PSX scene at> www.facebook.com/ScriptedArts1337

============================================================================
Updates; 4.83 - encountered Errors but installed fine / Still QA flagged /
Unknown issue, Build log lost, but I remember it mostly &
have created a "Patches" picture in the 4.83 (For Debugging.) folder in the
Gdrive link. (Do not install this as I have been stuck on 4.83 since I did, 
I keep recieving the following errors;

Whilst installing a CFW or OFW from the XMB
8002f957 update debug on
80029c9c update debug off

And I encounter a 80010017 error when I try to run my pkgs..
(I have tried running a disc, It worked perfectly, So I am unsure of the issue)
I cannot try recovery mode atm as I dont have a native ps3 controller, I will update
when I do.

when trying to run most of my packages / install any
firmware (I am not trying 4.83 OFW. I am also still QA flagged, so I am 
sure there is a fix for this, Thus I am uploading the 4.83 pup / decrypted 
pup so that if you wish you may have a look.

I will update if I fix it / figure out what is wrong, but until then I cannot
continue building the 4.83 CFW as my unit is currently faulty, And its the 
the only unit I have available! and I dont want to release anything I cant
test myself first (Except this for any devs. 4.83 is currently NOT FOR RELEASE.
Ignore it. Unless you are looking to investigate this issue, and have a method
to easily reverse the effects such as a hardware flasher / FSM. all dependant on
the current situation of course. 

I can still unhide Debug settings / Install pkg files under settings with
the button combo, pkgs install fine, only encountered errors with 2, but 
anyway, I or someone can hopefully fix this mess, Its like a CustomOFW at 
this rate xD

*cough* pseudobrick *cough* ;)
============================================================================
Changelog; 

4.82 - 0.11 (Initial Build)
PATCH: XMB - Miscellaneous
Add "Install Package Files" icon to the XMB Game Category
Add "/app_home" icon to the XMB Game Category

Changes to LV0 / LV1 / LV2	

Patch LV0 LDRS to disable ECDSA checks in ALL LV0-loaders,

Patch LV0 appldr to disable lv2 memory protection,

Patch LV1 for peek/poke support (unused lv1 calls 182 and 183),

Patch LV1 to allow mapping of any memory area (Needed for LV2 Poke),

Patch LV1 to remove LV2 protection,

Patch LV1 to disable CoreOS Hash check. Product mode always on (downgrader),

Patch LV2 to add LV1 Peek&Poke system calls (LV1 peek/poke patch necessary),

Patch LV2 to add Peek&Poke system calls,

Patch LV2 with misc ROGERO patches,

Patch LV2 to implement hermes payload SC8 /app_home/ redirection & embedded app mount,

Patch SPU PKG Verifier to disable ECDSA check for spkg files (spu_pkg_rvk_verifier.self),

Patch SPP Verifier to disable ECDSA check (spp_verifier.self),

Patch SPU Token Processor to disable ECDSA check (spu_token_processor.self),

Patch advanced Remote Play,

  Patch premo modules to enable Remote Play,
  
  Patch game_ext_plugin module to enable Remote Play,

PATCH: Patch translations- fix typos, change strings, replace languages,

  Fix a typo in the Italian localization of the sysconf plugin,

Patch VSH - Miscellaneous,

Patch VSH with ROGERO patches,

Patch to allow running of unsigned applications (3.xx/4.xx),

Remove CINAVIA Copy Protection on HDD Content,

Re-enable GAMEBOOT sound and animation on 3.00+ MFW,

  Patch game_ext_plugin.sprx to re-enable gameboot,
  
Patch Self(s) to Enable FSELFS on CEX,

======================================================================

3.55 - 0.11 - initial build

LV0 LDRS to disable ECDSA checks in ALL LV0-loaders, 

LV0 appldr to disable lv2 memory protection,

LV1 to to allow mapping of any memory area,

LV2 to add LV1 Peek&poke syscalls,

LV2 Peek&poke syscalls,

Misc rogero patches,

hermes payload SC8 /app_home/redirection & embedded appmount,

Patch SPU PKG verifier to disable ECSDA check,

Patch SPP verifier to disable ECDSA check,

Patch SPU token processor to disable ECDSA checl,

VSH patched with rogero patches,

Patched to allow installation / running of unsigned/Debug packages,

Renabled Gameboot sound and animation on 3.00+,

======================================================================
