KillTrack
=========

KillTrack will keep track of how many times you've killed various mobs.

The main way to see this info is on tooltips. As you hover over any killable mob, the kill count will be displayed on the bottom of the tooltip.

There is also a friendly list that you can bring up to display **all** mobs with their NPC id, global kill count and kills on the current character.
Note that the list will only load 100 entries at a time due to lag issues.
Loading more than 200 entries will most certainly cause severe lag.

You can open the list with the command /kt list.

Kill Timer
----------

Ever wanted to track how many kills you accumulate within a certain time? You can do so with KillTrack.

You simply tell it how long to track, and a window will pop up listing number of kills, time left, kills per minute and kills per second.


Kill Records
------------

When you've killed a certain mob a certain number of times (1000 by default), KillTrack will notify you with a small gratulation message!

If you have the AddOn Glamour installed, it will show in the style of a guild achievement.

To change the threshold, use the command /kt threshold \<threshold\>, where \<threshold\> is the new threshold.

E.g: If you set the threshold to 100, then after you've killed a mob 100 times, it will notify you. And continue to notify you for every 100th kill.

Immediate Frame
---------------

By using the command /kt immediate (or /kt i for short), you will get a small frame that shows you how many kills you've made since running the command. This can be useful for times when you need to kill a certain number of mobs, but do not wish to reset your session statistics. Simply run /kt i and it will track how many kills you do until you close it, reopening the frame will reset the count.

Feedback
--------

If you have any suggestions, bug reports, complains et.c, please make a new issue here on GitHub.  
I would prefer if you use the Issues page here on GitHub instead of the ones on Curse/WoWInterface.

Dependencies
------------

KillTrack depends on [AceGUI-3.0](http://www.wowace.com/addons/ace3/) (and therefore also [Libstub](http://www.wowace.com/addons/libstub/)) for creating its GUI elements.

External links
--------------

[KillTrack on Curse](http://www.curse.com/addons/wow/killtrack "KillTrack - Curse")  
[KillTrack on CurseForge](http://wow.curseforge.com/addons/killtrack/ "KillTrack - CurseForge")  
[KillTrack on WoWInterface](http://www.wowinterface.com/downloads/info20509-KillTrack.html "KillTrack - WoWInterface")

All images of the AddOn will be kept on Curse or WoWInterface.
