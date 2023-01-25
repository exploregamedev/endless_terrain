# Endless terrain tutorial

In this [Youtube tutorial](https://youtu.be/1jNt91A2PW0) you will build a simple 3D "Endless Runner" mechanism in Godot 4.
Completeing this tutorial will give you a great starting point to build your own endless runner 3D game.

## A terrain "conveyor" belt
This is one strategy to accomplish an endless runner; the conveyor belt strategy.

In our game style, the player is alwasy facing forward.
We build a "catalog" of terrian blocks.  When the game starts we load in a set of terrian blocks and start moving them in unison towards the player.

As the game progresses, as terrian falls behind the field of of the player, we remove it from the scene as it serves no futher purpose.  At the same time, we add another terrian block at the far horizon.

This cycle continues givin the illution of infinite terrian.


![](docs/terain%20conveyor%20demo.png)
