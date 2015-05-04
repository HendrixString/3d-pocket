# 3D Pocket: #

---


a 3D engine developed for Pocket PC and Symbian

&lt;BR&gt;


phones a while ago.
some of the tech specs:
  * VSD Algorithms: This is a grid based **Portal engine** with a **Quad-Tree** culling system. can render huge worlds without loosing frame rates.
  * Rendering is software based only (no GPU Hardware is needed at all).
  * Extremely portable and fast (uses fixed point math also - no FPU needed).
  * grid based engine = no need for Z-Buffer :-)
  * dynamic per vertex RGB lighting.
  * Linear fog.
  * full collision detection.
  * support for 3rd person camera.
  * support for .MD2 keyframe animation.

  * the engine runs on top of **POCKET HAL**, a library for accessing Symbian and mobile windows screen buffer.

  * Compiled on Visual studio for Pocket PC.
  * the engine can be ported as well to any platform.
  * no world editor was created. world data is coded in data structures within GL\_Data.cpp. please consult the following for understanding the data structures:
    1. **GL\_Types.h**
    1. **GL\_Struct.h**
    1. **GL\_Room\_type.h**
    1. **GL\_Data.h**

**further notes:**
> the engine architecture and technology is very
> similar to the engine, that powered the first 3
> Tomb Raider games. well worth the study for those who
> are into engine design and VSD algorithms.

<a href='http://www.youtube.com/watch?feature=player_embedded&v=HSl9Gs2dr-M' target='_blank'><img src='http://img.youtube.com/vi/HSl9Gs2dr-M/0.jpg' width='425' height=344 /></a>