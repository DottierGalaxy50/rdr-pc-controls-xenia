# rdr-pc-controls-xenia
This script introduces PC controls into xenia canary for Red Dead Redemption Game of the Year Edition (Single Player and Undead Nightmare). It has his own trainer where key binds, sensitivity and other settings are changed.

This was intended to be used on Xenia Canary @ec267c358 (6/13/24) for RDR GOTY, however, you could try using it on a different version of xenia or the other versions of RDR.

The script gives full control of the camera like a native PC game and removes any kind of aim assist the game has, however, there are cases where instead of using the new mouse camera, L-Stick inputs will be simulated to move the camera instead, like for mounted weapons, has they really didn't needed their own custom camera, or when we take cover for the first time, has we can only locate the code related to the in-cover camera once we taken cover at least once.

## How to use
Once downloaded, you can extract the files anywhere, but i recommend just extracting them inside xenia canary's folder so you can use the batch files it comes with, the batch files only need to be edited to add the path of the game. Opening the batch file will launch the game and the trainer.

The trainer has a System Tray icon (hidden icon). By default, the script gets enabled automatically and the trainer gets hidden once it detects the game is running, if you want to show the trainer again use the icon on the System Tray.

The script activates only after we are on the main menu, the script takes about 3 seconds to activate (depends on your system), and once it has loaded it will automatically hide the cursor and capture the inputs if xenia was the foreground window.

The script can be enabled/disabled at any time, but i don't recommend doing it. By default, the trainer will close itself if xenia stops.

The mouse can only be captured if we either click inside xenia's window, or if we change fullscreen (F11).

## Bugs, issues & details
If the trainer crashes and closes, xenia may need to be closed if his memory didn't got restored before the trainer closed, try re-opening the trainer and see if the script can be enabled.

If a 'lua engine' window opens, that means something failed and the trainer needs to be restarted, close the lua engine window first and then close the trainer, otherwise the trainer may not close entirely and it will need to be manually closed through the task manager.

Anything on top of the window, even while on fullscreen, will be able to be clicked (like a notification or the task bar).
