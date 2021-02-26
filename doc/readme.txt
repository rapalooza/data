====================================================================
RagnarokOnline Patcher Lite
(c) 2009-2021 Ai4rei/AN

====================================================================

== About ===========================================================

Replacement for Gravity's Patcher. Works faster and doesn't consume
your entire memory for just seeing it crashing, aside from this, it
works almost exactly as the official patcher does, so that it
shouldn't break, unless Gravity changes something vital to their
patcher. It also protects from some remote attacks, present in
official patcher's rgz processing code.

== Release Notice ==================================================

This is a release with fixed patch information. You are encouraged
to report experienced crashes and/or misbehaviour to the related
board topic.

== Known Bugs & Issues =============================================

None.

== Requirements ====================================================

 -  Operating system:
     -  Windows 95
        > Requires at least IE3 installed for WinInet dependency.
     -  Windows 98
     -  Windows NT (untested)
     -  Windows ME
     -  Windows 2000
     -  Windows XP
     -  Windows Vista
     -  Windows 7
     -  Windows 8 (except RT)
     -  Windows 8.1
     -  Windows 10
     -  Windows Server (except Core)
 -  Hardware:
     -  32-bit or 64-bit platform
     -  Disk space and RAM requirements < 1 MB
        > Downloaded patches cause additional requirement on disk
        > space.
        > Processed patches cause additional requirement on RAM, but
        > typically not more than 10 MB
     -  Stable internet connection
     -  Keyboard or a pointing device

== Usage ===========================================================

RSU does not require any installation. Minimum required files for
running are rsu.exe and rdata.grf. You should also add an existing
patchRE.inf to avoid entire re-patching of the grf.

The patch process will start after clicking button 'Start' and can
be aborted at any time by pressing 'Cancel' unless the button is
disabled. The patch process is completed once the message 'Patch
process completed' or any kind of failure is displayed in the status
line and the 'Cancel' buttons turns into 'Close'.

If you press 'Close' while SHIFT key is held, downloaded patches
will be preserved.

== Command Line Parameters =========================================

The official patcher supports (and/or supported) certain command
line parameters, that have been adapted in RSU. Those starting with
'/' are adapted from first official patcher (the one without skins),
the others from second and current official patcher (with skins).

/test       Allows to bypass 'deny' in 'patch_allow.txt', which is
            set during maintenance on official servers, to prevent
            you from patching. It is not recommended to use it,
            unless you really know, what you are doing, since you
            might receive corrupted or invalid patches, that aren't
            available later.

/repak      Forces complete rebuild of the main GRF archive
            reclaiming all wasted space. Note, that this process may
            take a while for larger archives and you must have at
            least same amount of space free, as the main GRF archive
            takes up. The patcher asks you automatically about
            repacking, once too much wasted space is detected inside
            the archive.

donut       Same as /test.

Following command line parameters are not in official patchers.

/autostart  Makes the patcher start the patch process automatically
            instead of waiting for you to press start. Intended for
            shortcut usage.

/testpak    Tests the entire main GRF archive for errors, like
            invalid header, file table or corrupt files. Note, that
            this process may take a while for larger archives and it
            is normal that an amount of about 3~15 files do not work
            correctly. The client doesn't bother about it, since it
            doesn't check for any extraction errors from uncompress.
            Note: In older releases this switch was called /test,
            due to an initial misconception.

/updateonly Same as /autostart, except that it will close the
            patcher after the patch process.

== Updating & Removal ==============================================

For updating you have to check the website for newer versions. Just
overwrite the old files with the new ones.

If you no longer want to use the patcher, simply delete rsu.exe,
asrdll.dll (optional), associated docs and any possible plugins. RSU
does not store any user data in the registry or anywhere else.

== Disclaimer ======================================================

The executable ( rsu.exe ) is guarantied virus/spyware/callback-free
when downloaded from it's primary location ( nn.ai4rei.net ).
This DOES NOT apply to any mirror, that might be provided for this
download.

You use the application at YOUR OWN RISK. You are always encouraged
backup your data before using this beta release, especially the main
GRF. I'm not liable for any direct or indirect damages on software
or hardware ( including, but not limited to data loss, corruption,
crashes ), that may arise from using this piece of software. If you
don't agree with this, delete this application entirely.

== Contact =========================================================

Website: http://ai4rei.net/p/rsu
Support: http://ai4rei.net/p/bbs

== Legal Stuff & Used Components ===================================

Any Ragnarok Online related graphics and materials are Copyright (c)
2002-2021 Gravity Co., Ltd. & Lee Myoungjin. Ragnarok Online is a
trademark of Gravity Co., Ltd.

Uses zlib 1.2.11 library for (de)compression Copyright (C) 1995-2017
Jean-loup Gailly and Mark Adler ( zlib.net ).

====================================================================