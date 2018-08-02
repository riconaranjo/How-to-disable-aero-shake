# How to disable Aero Shake

If you are like me, and are incredibly annoyed by the fact that windows will minimize all windows if you shake a window around. I often do this while waiting for a large file to transfer or laoding screen on a webpage.

Here is how you can disable this on Windows 10 Pro.

1. Go to **Run**, press <kbd>command</kbd> + <kbd>r</kbd>
2. Type gpedit.msc
3. Go to **Local Group Policy Editor**
4. User Configuration > Administrative Templates > Desktop
5. Double-click on **Turn **off Aero Shake window minimize mouse gesture
6. Select **Enabled**, and click **OK** — _[you are enabling the turn off setting]_
7. Restart your computer, for the changes to take effect.

_Pretty simple._ Why this feature exists, is beyond me.
