# rdr-pc-controls-xenia

> **I would recommend using the [Mousehook](https://github.com/marinesciencedude/xenia-canary-mousehook) fork of Xenia Canary instead of this as it has support for most RDR versions and many other games, as well as multiplayer support. Mousehook's RDR support is also partially derived from this so it's better using it overall even if you are only interested in RDR.**

This script introduces PC controls into Xenia Canary for Red Dead Redemption Game of the Year Edition (Single Player and Undead Nightmare). It has his own trainer where key binds, sensitivity and other settings are changed.

This was intended to be used on Xenia Canary [@ec267c348](https://github.com/xenia-canary/xenia-canary/releases/tag/ec267c3) (6/13/24) for RDR GOTY Edition, however, you could try using it on a different version of xenia or the other versions of RDR.

The script gives full control of the camera like a native PC game and removes any kind of aim assist the game has, however, there are cases where instead of using the new mouse camera, L-Stick inputs will be simulated to move the camera instead, like when we take cover for the first time, as we can only locate the code related to the in-cover camera once we have taken cover at least once.

The trainer may get flagged by the anti-virus as malware, this is because Cheat Engine is used as a hacking tool, in that case, you will have to make an exception for the file.

Because of that same reason, anti-cheats may flag the trainer as well, therefore, i recommend not having any other games open when the trainer is running to avoid any issues.

## How to use
Once downloaded, you can extract the files anywhere, but i recommend just extracting them inside xenia canary's folder so you can use the batch files it comes with, the batch files only need to be edited to add the path of the game. Opening the batch file will launch the game and the trainer.

The trainer has a System Tray icon (hidden icon). By default, the script gets enabled automatically and the trainer gets hidden once it detects the game is running, if you want to show the trainer again use the icon on the System Tray.

The script activates only after we are on the main menu, the script takes about 3 seconds to activate (depends on your system), and once it has loaded it will automatically hide the cursor and capture the inputs if xenia is the foreground window.

The script can be enabled/disabled at any time, but i don't recommend doing it. By default, the trainer will close itself if xenia stops.

The mouse can only be captured if we either click inside xenia's window, or if we change Fullscreen (F11).

## Bugs, issues & details
If the trainer crashes and closes, xenia may need to be closed if his memory didn't got restored before the trainer closed, try re-opening the trainer and see if the script can be enabled.

If a "Lua Engine" window opens, that means something failed and the trainer needs to be restarted, close the Lua Engine window first and then close the trainer, otherwise the trainer may not close entirely and it will need to be manually closed through the task manager.

Anything on top of the window, even while on Fullscreen, will be able to be clicked (like a notification or the task bar).

Some patches or settings may have conflicts with the script. If you are having problems, try using Xenia's default settings with no game patches.

## Thanks to

zhm86: for making the [Camera mouse controller for Ryujinx](https://gamebanana.com/scripts/11752) script that inspired me to make one for xenia.

Cheat Engine: for the software and documentation.

And all the people that asked questions on forums and the people who gave them solutions that i could use.
