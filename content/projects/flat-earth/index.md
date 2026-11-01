+++
title = "Flat Earthers Dream"
date = 2021-11-01
summary = "Physics based first person shooter"
main_image = "images/flat-earth/idle-enemy.png"
categories = ["personal"]  # optional
tags = ["gamedev", "opengl"]  # optional

[params]
  featured = false # Show in featured section on homepage
  weight = 3  # Order in featured section (lower = first)
  showInPostList = false # Show in timeline lists alongside blog posts
+++

Dive deep into a dreaming subconscious of a flat earther.\
Protect the (flat) Earth with your kinetic powers!\
Fight off hostile intruders by pushing them into the void!\
DON’T. LET. THEM. TOUCH. YOU!

{{< figure 
    src="images/flat-earth/preview.gif" 
    alt="GIF of a Gameplay Preview"
    position="center"
    class="post-image"
>}}

### About the project 
This is a first person shooter game inspired by Devil Daggers written in C++ using OpenGL. In _Flat Earthers Dream_ the player has to last as long as possible The game has no fixed end, it only gets harder with every passing second as amount of spawning enemies increases. Simplified physics simulation has been implemented for somehow realistic interaction between enemies and player’s power. Player will die if they make contact with any of the enemies or falls out of the map.

There are two type of enemies: 
- _Idle_ - stands almost still, keeping an eye on the player 
- _Chasing_ - follows the player around until it catches them.

{{< figure 
    src="images/flat-earth/idle-enemy.png" 
    alt="Screenshot showing off idle enemy."
    position="center"
    class="post-image"
>}}

{{< figure 
    src="images/flat-earth/enemy-wave.png" 
    alt="Screenshot showing off enemy waves."
    position="center"
    class="post-image"
>}}

{{< figure 
    src="images/flat-earth/idle-chasing.png" 
    alt="Screenshot showing off two type of enemies."
    position="center"
    class="post-image"
>}}

{{< figure 
    src="images/flat-earth/game-over.png" 
    alt="Screenshot showing off a GAME OVER screen."
    position="center"
    class="post-image"
>}}
