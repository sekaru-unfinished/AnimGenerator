# AnimGenerator

Class for creating an animation based off a spritesheet for libGDX.

Usage:
```java
float animSpeed = 0.1f;
int fw = 32; // frame width
int fh = 64; // frame height
Animation anim = new Animation(animSpeed, AnimGenerator.gen("sprites/player.png", fw, fh));
```
