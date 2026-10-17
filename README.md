# MG3
## Devlog
1. The default values for floats and ints are 0, bools are false, and strings are just nothing. 

2. the update method just seems to be called every frame by Unity itself. I never call to it, but it always seems to run due to Unity. It's the same like in Java. 

3. The TimerText class uses the timer script by (in my best words) using it to make its own timer seperate from the other classes. It calls to the BeginTimer method to set a timer and uses the Timer's "Update" method to count down from the initial time set. Then, it uses it's own "Update" method to display the time left while the Timer class is counting down. 


## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)