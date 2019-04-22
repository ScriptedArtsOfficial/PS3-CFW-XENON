
PS3 Custom Firmware = XENON - 
Located at; Reuploading soon due to updates to code and more.

This is a Custom Firmware for the Playstation 3 
that I am working on,
currently it is in alpha stage. 
(It is a full CFW but currently resides as a CEX only with rogero patterns)
It is due to be updated
(Will reach v1.00 at least) And, will recieve customisation,
hopefully will port Cobra payloads and possible DEX varients as well,
but all really depends on my time as I am busy a lot of the time,
and will be working on PS4 predominently within the console scene!

============================================================================

Check out my other work and information
on my work on PSX scene at> www.facebook.com/ScriptedArts1337

============================================================================
Updates; 

4.84
I am in the process of planning on working on a 4.84 CEX Fw, I will post more information soon.

4.83 
- encountered Errors but installed fine / Still QA flagged /
Unknown issue, Build log lost,
but I remember it mostly &
have created a "Patches" picture in the 4.83 (For Debugging.)
folder in the Gdrive link. 
(Do not install this as I have been stuck on 4.83 since I did, 
I keep recieving the following errors;

Whilst installing a CFW or OFW from the XMB
8002f957 update debug on
80029c9c update debug off

And I encounter a 80010017 error when I try to run my pkgs..
(I have tried running a disc, It worked perfectly, So I am unsure of the issue)
update through Recovery mode did not work on this fw, managed to install 4.84.2 Hybrid Firmware, 
and Rejailbreak.

I was still QA flagged, so I am 
sure there is a fix for this, Thus I am uploading the 4.83 pup / decrypted 
pup so that if you wish you may have a look.
Otherwise, I will update if I fix it / figure out what is wrong, but until then
I will just start 4.83 from scratch.

I dont want to release anything I cant test myself first 
(Except this for any devs. 4.83 is currently NOT FOR RELEASE.
Ignore it. Unless you are looking to investigate this issue, and have a method
to easily reverse the effects such as a hardware flasher / FSM.
all dependant on the current situation/issue of course. 

*cough* pseudobrick *cough* ;)
============================================================================
Changelog; 
4.82 V0.11a - Xenon Firmware - By ScriptedArts / OneKubbYT

PATCHES:

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
