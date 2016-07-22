# LEAP - Tennis
--------------------
Listen, lEArn, Play.

Breaking the accessibility barriers for blind children

Hundreds of electronic games for children are existing nowadays and almost all require that users have good eyesight. But blind children are still children! They have right to happiness and to a quality life. Also, they seek for acceptance of their individuality and recognition of their increased needs for accessibility and autonomy.

LEAP Tennis is a simple simulation of a tennis game, especially modified for visually impaired people. It can be played solely with the use of audio. Note that the usage of headphones is mandatory. It is a [We are all citizens](http://www.weareallcitizens.gr/index_en.html) project, funded by [EEA grants](http://eeagrants.org) and [Bodossaki Foundation](http://www.bodossaki.gr/en/home). 

* [SciFY](http://www.scify.gr/site/en/)
* [Lab. of Audiovisual Signal Processing, Dept. of Audiovisual Arts, Ionian University](http://epoasi.eu/en/)

## Current stable version
-------------------------
Current version is 1.1

## Extra Soundsets
------------------
Under the folder "Extra Soundsets" you will find two female voice soundsets, one in Greek and one in English. You will also find the source code for a soundset manager specifically for leap games. Under the "compiled" folder you can also find compiled versions of the soundset manager for your convenience.

## Extra Soundsets Folder Structure
-----------------------------------
When creating a new build, if you want to support the usage of external soundsets, create a folder next to the games Data folder. The folder should have the same name but with the suffix Soundsets instead of the suffix Data (e.g. if building the project "tennis_lin" create the folder "tennis_lin_Soundsets" next to the folder "tennis_lin_Data"). Directly under this folder add the compiled version of the soundset manager, the README.txt and sound_settings_Tennis.xml files from the src folder, and any soundset folders you want to include.

## Dependencies
---------------
Is built with the free version of the UNITY3D engine and, apart from it, there are no other dependencies.

## Executable files
-------------------
The executable files for Linux, MAC OS and Windows can be found at www.gamesfortheblind.org