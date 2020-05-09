﻿# obs-progress

A plugin for OBS Studio that shows progress of all media files in the active scene, including audio and video. A progress bar, along with elapsed time, total time, and remaining time, is shown for each media source. Progress is displayed in a standard OBS dock that can be floated, pinned, hidden, etc.

![screenshot](https://i.imgur.com/aKYiKww.png)

Here it is pinned above the Scene Transitions and Controls docks. The title of the dock displays the scene name, while the text above the prgress bar(s) show the source name.

# Issues

* Currently, OBS cannot remember the dock position of plugins, because docks are added at each startup.
* obs-progress plugin ocasionally causes crash on shutdown. Exception comes from Qt code.
