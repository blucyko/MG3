# MG3
## Devlog
**1. What are the default values for floats, ints, bools, and strings? To find out, try adding one variable of each type as a member variable to the Timer class, and see what default value for each variable shows up in the Inspector.**  
The default values for floats, ints, bools, and strings are 0, 0, false, and " ". I found this out by adding some test variables of each type including the [SerializeField] element, in order to see the default value of the variable in the Inspector.

**2. How does the Update method get called- is your code supposed to call it in this assignment, or does it get called some other way?**  
The Update method gets called as a built-in method from Unity that runs every frame.
   
**3. Explain how either the KickWeapon or TimerText class uses the timer. Mention the Update() method.**  
The TimerText class uses the timer in its Update() method to check whether the timer has run out. If it runs out, based on checking the _gameTimer object of the Timer class by calling _gameTimer.GetTimeLeft(), then the GameOver() method is called. This then sets the gameOver text to true and the player's gameOver state to true.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
