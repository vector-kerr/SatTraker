# SatTraker

EXPERIMENTAL!  USE AT YOUR OWN RISK! Automatic orbit and video-based tracking of satellites with GOTO telescopes.  See Astronomy Live on YouTube for details.
https://www.youtube.com/messierhunter




# Updates by vector-kerr

* Add `settings.ini`
  * See `settings.example.ini` for... an example.
* Add ZWO ASI Camera Library
  * ***THE ASI LIBRARIES MUST BE ADDED IN THE LIBRARIES FOLDER FOR THIS TO WORK***
  * ***THE ZWO SETTINGS.INI FILE MUST HAVE `[ZWO] ENABLED=1` FOR THIS TO WORK***
  * This is dumb and limited, and currently expects a monochrome camera
  * Images can be resized with `settings.ini` config if they come out heinously large from the camera
