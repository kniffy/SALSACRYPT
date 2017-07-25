# SALSACRYPT

like it says on the tin, I made a quick fork of PERPLEX's old blowcrypt script
to use shit that aint blowfish.. schneier himself says to not use it anymore
:)

before you make use of this you need to get FiSHDANCE and compile the shit,
and edit the tcl to load it. assuming you put it under scripts/ in your eggbot
dir then you dont have to lift a finger. :)

please read the FiSHDANCE doc and set a sane key; i ran into loads of issues
with very short keys, so don't be dumb and ask anyone why the shit doesnt work

as a bonus i included a fork of ngBot's Blow.tcl which does the same shit as
this, but maybe you prefer it over this, idk.

before anyone asks, i know that output of something really big like !help with
ngBot is broken by the timestamp check.. if anyone has a bright idea that isnt
increasing the amount of time allowed let me know, since i probably wont fix
it myself. dont ask me about keyex either.

have fun, kids.

