---
startdate: 2015-06-17
layout: portfolio
title: The Eternity Engine
---
![The Logo]({{ site.baseurl }}/portfolio/images/EELogo.png)

The [Eternity Engine](https://github.com/team-eternity/eternity) is a GPL Doom source port maintained by
James "Quasar" Haley and Stephen "SoM" McGranahan. I took an interest to the project in late 2014, and
in 2015 started working on a feature according to a specifcation provided by Quasar. On August 1st 2016
I was made an official member of Team Eternity due to my continued contributions. Since working on the
engine I have made changes including (but not limited to):

* Added a system where the type of blood spawned could be specified through EDF.
* Slimmed down portable v/snprintf
* Changed rotating polyobjects such that they correctly rotate for angles of 180&deg; or more
* Fixed an issue where attached 3D middle textures would desynchronise from their attached surface
* Changed scripts that open on map start to where they wait until after the screen wipe finishes
* Added several action special
* Added a fully functional system that allowed for the picking up, display, and use of items

If you wish to find out more about the Eternity Engine, please check out [its  dedicated wiki](eternity.youfailit.net/),
or for a more succinct overview check out its page on the [Doom Wiki](http://doomwiki.org/wiki/Eternity_Engine).

A list of all commits I have made to the project are available
[here](https://github.com/team-eternity/eternity/commits?author=Altazimuth).