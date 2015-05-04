# 3D-Pocket
a 3D engine developed for Pocket PC and `Symbian` enabled devices at 2003.
phones a while ago. some of the technology specifications:

* VSD Algorithms: This is a grid based Portal engine with a Quad-Tree culling system. can render huge worlds without loosing frame rates.
* Rendering is software based only (no GPU Hardware is needed at all).
* Extremely portable and fast (uses fixed point math also - no FPU needed).
* grid based engine = no need for Z-Buffer :-)
* dynamic per vertex RGB lighting.
* Linear fog.
* full collision detection.
* support for 3rd person camera.
* support for .MD2 keyframe animation.
* the engine runs on top of POCKET HAL, a library for accessing Symbian and mobile windows screen buffer.
* Compiled on Visual studio for Pocket PC.
* the engine can be ported as well to any platform.
* no world editor was created. world data is coded in data structures within GL_Data.cpp. please consult the following for understanding the data structures:
  1. GL_Types.h
  2. GL_Struct.h
  3. GL_Room_type.h
  4. GL_Data.h
  
further notes:<br/>
the engine architecture and technology is very similar to the engine, that powered the first 3 Tomb Raider games. well worth the study for those who are into engine design and VSD algorithms.

### Demo

<a href="http://www.youtube.com/watch?feature=player_embedded&v=HSl9Gs2dr-M
" target="_blank"><img src="http://img.youtube.com/vi/HSl9Gs2dr-M/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

### Terms
* completely free source code. [Apache License, Version 2.0.](http://www.apache.org/licenses/LICENSE-2.0)
* if you like it -> star or share it with others

### Contact Author
* [tomer.shalev@gmail.com](tomer.shalev@gmail.com)
* [Google+ TomershalevMan](https://plus.google.com/+TomershalevMan/about)
* [Facebook - HendrixString](https://www.facebook.com/HendrixString)
