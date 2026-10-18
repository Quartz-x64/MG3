# MG3
## Devlog
1. int=1, float=0, bool=false, string=null.
2. Unity calls Update once per frame while the component is enabled. We normally don’t call it ourselves.
3. A timer can track elapsed time by adding Time.deltaTime to a float in Update. KickWeapon could use that elapsed time to decide when another kick is allowed, or TimerText could read the timer and display it. The class that owns the timer updates it each frame through Update, while the other class reads its value.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
