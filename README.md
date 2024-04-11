# VlcMedia

this is folked from  [helmers-timo/VlcMedia](https://github.com/helmers-timo/VlcMedia)


## About

Tested the public RTSP stream and it didn't work properly
Replace the VLC-4.0.0 used by the source with the library of the current stable version of VLC-3.0.20

For more information, we recommend that you refer to the original repository

## Changes

Convert to Engine Version 5.2.1
Replace dll with VLC 3.0.2 version



**IMPORTANT**: Please note that this repository contains pre-compiled binaries
for libvlc and its plug-ins, which are licensed under LGPL. This means that you
cannot create monolithic builds of your game without violating LGPL, the UE4
EULA or both. The libvlc libraries must remain dynamic libraries that are bound
at run-time - static linking is not allowed - and the licensing related files in
*/ThirdParty/vlc* must be retained.

This also means that this plug-in cannot work on platforms that do not support
dynamically linked libraries (i.e. iOS, HTML5) or do not currently implement
support for it (i.e. Android, XboxOne).

Epic is in the process of adding plug-in support to monolithic builds, but there
is no ETA yet. Once this is supported, you will be able to distribute monolithic
game and server builds with VlcMedia, provided that the libvlc libraries and
plug-ins remain as separate DLLs.


