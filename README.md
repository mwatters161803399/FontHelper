FontHelper
==========

(Work in progress).

A small utility (providing an OS X framework and an iOS library) for
obtaining system font data on OS X and iOS devices.  Will provide
methods to obtain a dictionary of font tables (i.e., for truetype
fonts).  Will cache contents of (large) table of glyphs to the
filesystem and indicate the cache filename in the returned dictionary.

Purpose: access (non-embedded) system font data on iOS for use with
non-Apple graphics libraries needing direct access to font data (e.g.,
zpb-ttf).
