# cub3d 

A 3D mini game named Blubble. 

[![svan-ass's 42 cub3d Score](https://badge42.vercel.app/api/v2/clfladlx3000608l58byc7e5w/project/2700072)](https://github.com/JaeSeoKim/badge42)

The inspiration for this two-person team project came from Wolfenstein 3D, the first FPS game. This project provides an opportunity to delve into the technique of ray-casting, allowing you to create a dynamic view inside a maze. For the bonus we only made animations and a mini map.

<img src="https://github.com/steryu/Cube3d/blob/main/textures/gif/Cube3D_short.gif" width="60%" height="60%">

### **Usage**
- `W, A, S, D` to move
- `<- ->` to rotate the point of view
- `SHIFT` to sprint
- `ESC` - to exit the game

### **The Game**
The first thing we did was going trought this amazing tutorial by Lode Vandevenne. Without it we would've had a hard time.
The tutorial provides a comprehensive introduction to the technique of ray-casting in computer graphics. It
begins with an overview of the basic concepts involved in ray-casting and explains the algorithm behind it in detail.
Because of the tutorial we learned topics such as setting up the screen, creating a 2D map, casting rays from the player's position, detecting collisions with walls, and implementing textured walls.

- **Textures**\
The idea was to have the game be underwater, so the self made pixel art reflected an aquatic theme, aptly named blubble (a combination of "blub" and "bubble"). I made four different images for each cardinal wall direction. Only the image featuring fishes was made to be animated, hopefully enhancing the nature of the environment more :).

 - **The mini map**\
My teammate had skillfully coded the mini-map, using the 2D array to create an x-y grid. Now we had the coordinates of open spaces and walls and were able to texture the map, by placing the pixels at the bottom right of the map. Then, by saving the player's position at every move, we could update and render the mini-map with each step.

<img src="https://github.com/steryu/cube3d/blob/main/textures/gif/cube3D_animations.gif" width="60%" height="60%">

### **How to compile**
``` sh
make && ./cub3d maps/[INSERT_MAP].cub
```

### **Contributors**
<table>
  <tr>
    <td align="center"><a href="https://github.com/Raavkoper"><img src="https://avatars.githubusercontent.com/u/94134595?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Raav Koper</b></sub></a><br /><a
  </tr>
 <table>
