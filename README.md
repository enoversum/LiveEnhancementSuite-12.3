# LiveEnhancementSuite-Live12
**Live Enhancement Suite (LES) v1.3.5** updated for Live 12 with 3 new added keybinds (forked from jastro). 
Improvements: 
* Now compatible with Live 12.3 via **improved right-click menu search routine** that works again with better timings.
* The optional **closing of the browser** after a search is now realised via the _Ctrl + Alt + B_ shortcut instead of previously via mouse click with coordinates (which tended to fail). Settings for this (resetbrowsertobookmark) are still respected, coordinates aren't.
* **Buplicate** has a new shortcut (Ctrl + Shift + B) to allow for Bouncing to new track via Ctrl + B.

## New features:
* **Close and fold:** Closing the window after loading the device (VST2/VST3 only), and folding the mini window in the device chain at the bottom. Can be used together or singular. Just add ` -close` and/or ` -fold` (with a leading space) to the second line of your entries in `menuconfig.ini`. Both are optional. 

Example entry for a plugin:

`Arturia Pigments
Pigments vst3 -close`
_Pigments closes after loading_

`Arturia Pigments
Pigments vst3 -fold`
_Pigments' window in device view folds after loading_

`Arturia Pigments
Pigments vst3 -close -fold`
_Pigments closes and folds after loading_

This is an update to make LES work great again *cough* on Live 12.3, mainly for my own use, but hopefully beneficial for others as well. I'm not a proper AHK developer. But please let me know if you're facing any issues, especially with the new `-fold` and `-close` functionality, which might break on heavier Live sets and/or weaker machines. 

Link to original: https://github.com/LiveEnhancementSuite/LESforWindows
