Welcome to the TVRage Alfred Workflow
=====================================
### Version 1.0

This workflow is currently setup to run based on the tv keyword. It queries TVRage and returns information on the show. If you are using a hotkey, it will pass your current selection in OS X into the workflow.
![Alfred Workflow Example](http://i.imgur.com/oND1ufT.png)

Configuration:
--------------
* If you would like to switch the time from 12 hour to 24 hour or vice versa, use keyword 'enable12hr' or 'enable24hr'.

Returning Series:
-----------------
[*SHOW_NAME*] is a returning series. It is aired on [*AIR DAY*] at [*AIR TIME*] on [*TV NETWORK*].

Canceled/Ended Series:
----------------------
[*SHOW_NAME*] is canceled/ended. It ran for [*NUMBER OF SEASONS*] season(s) on [*TV NETWORK*].

TBD/On The Bubble Series:
----------------------
[*SHOW_NAME*] is on the bubble for being renewed. If it is renewed, it airs on [*AIR DAY*] at [*AIR TIME*] on [*TV NETWORK*].

Use of the Workflow
===================
This workflow can be called by the keyword "tv [*TV SHOW NAME*]". This will query the TVRage database and return results based on your query.

Features to be added:
---------------------
* TV Episode search — NOTE: functions, but slow. Trying to speed it up before hooking it up.
* ~~12 hour version (instead of current 24-hour time)~~
* ~~Create icon for TVRage workflow~~
* ~~Better Timezone support~~
* ~~[Alleyoop](http://www.alfredforum.com/topic/1582-alleyoop-update-alfred-workflows/) Support~~

Resources Used:
---------------
* [PHP TVRage Class](https://github.com/ryandoherty/PHP--TVRage)
* [Alfred App v2](http://www.alfredapp.com/)