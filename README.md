# cube3d 

A 3D mini game named Blubble. 

[![svan-ass's 42 cub3d Score](https://badge42.vercel.app/api/v2/clfladlx3000608l58byc7e5w/project/2700072)](https://github.com/JaeSeoKim/badge42)

The inspiration for this two-person team project came from Wolfenstein 3D, the first FPS game. This project provides an opportunity to delve into the technique of ray-casting, allowing you to create a dynamic view inside a maze. For the bonus we only made animations and a mini map.

<img src="https://github.com/steryu/Cube3d/blob/main/textures/gif/Cube3D_short.gif" width="70%" height="70%">

**Usage**
WASD for momevent
< > arrows to roate the point of view
SHIFT to sprint

**Devolopment process**
The first thing we did was going trought this amazing tutorial by Lode Vandevenne. Without it we wouldve had a hard time.
The tutorial provides a comprehensive introduction to the technique of ray-casting in computer graphics. It
begins with an overview of the basic concepts involved in ray-casting and explains the algorithm behind it in detail.

Because of the tutorial we learned topics such as setting up the screen, creating a 2D map, casting rays from the player's position, detecting collisions with walls, and implementing textured walls.

**Textures**
for the textures I made self made pixel art. The idea was to have the game be underwater, hence the name blubble (blub and blubble). I made four different images for the the north, south, east and west walls. only the image with the fish I animated.

### **How to compile**
``` sh
make && ./cube3d maps/[INSERT_MAP].cub
```
