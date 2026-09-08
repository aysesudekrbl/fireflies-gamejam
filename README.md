# Glow 

A 2D game jam project built with Unity and C# over ~5 days, where two fireflies are connected by a spring. Pull them together with the mouse, avoid obstacles, and keep the connection alive as long as you can.

**[Play it on itch.io](https://xxaerynn.itch.io/glow)**

This was one of my first hands-on projects in Unity, built while still learning the engine.

## Features

- **Spring-based movement** : a `SpringJoint2D` connects the two fireflies. Pulling them together tightens the rope, letting go loosens it.
- **Visual feedback** : a `LineRenderer` draws the rope between them, changing color based on tension (yellow when loose, red when stretched) and glow intensity based on distance.
- **Obstacle spawning** — obstacles spawn randomly from the top of the screen and get destroyed once they are off-screen.
- **Collision & game over** : hitting an obstacle ends the run and goes to a game over screen, with a retry button that resets back to the first scene.
- **Score system** : collectibles add to your score as you survive longer.
- **Menus & audio** : main menu, scene transitions, music, and sound effects.

## Tools Used
Unity, C#
