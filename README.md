MAELSTROM
=========

This is a very simple OO JavaScript Canvas Based GameEngine With An Example Game. 
It is the first JavaScript code that I have ever written, please be patient with
it. I want to use it here to demonstrate my skills progression over time. This is
my starting point (smile).

The small game which demonstrates that the game engine works, is a homage to
the beautiful old vector based game 'Asteroids'. This version pokes playful
fun at the sisyphean nature of the original game. A high score is bad, since
the score is the count of poor souls whos untimely demise is caused by your
sloppy asteroid cleanup job. Your ship has a dashboard that contains a stream
of messages your fellow earthlings -- the messages go through a mood shift of
the stages of grief as the situation gets more dire. When you fail, you are
stuck inside of the singularity technology that allowed your ship to respawn.
At that point, you can press space to maintain conciousness or choose to let
go.

This is the demo (Arrow keys to move, space to shoot):      
http://glitchland.github.io/maelstrom/

![Screenshot1](sprites/intro_screen.png?raw=true)
![Screenshot2](sprites/screen_shot_1.png?raw=true)

TODO
=========

- Add invuln on first level load
- Remove .init from engine, figure out nicer way to do that because it is cluttered
- Refactor the demo game, write a few more demos to demonstrate simple games/effects
- Move Radians to angles/ angles to radians out into helper functions
- Add GameObject age (if go > age die)

Resources Used During This Project
=========
2D Collision Detection      
https://developer.mozilla.org/en-US/docs/Games/Techniques/2D_collision_detection

2D Rotated Rectangle Collision      
http://www.gamedev.net/page/resources/_/technical/game-programming/2d-rotated-rectangle-collision-r2604

Rectangle Rotation On Canvas     
http://stackoverflow.com/questions/26389966/how-to-rotate-2-rectangles-in-a-canvas-at-the-same-time

Audio   
http://www.html5rocks.com/en/tutorials/webaudio/games/

Test Sound    
http://www.flashkit.com/imagesvr_ce/flashkit/loops/Techno-Dance/Rave/Trancy-AlaShook-10434/Trancy-AlaShook-10434_hifi.mp3

Laser Sound    
http://soundbible.com/1087-Laser.html

Main Music    
http://openmusicarchive.org/audio/In_The_Dark_Flashes.mp3

Death music    
http://openmusicarchive.org/audio/April_Kisses.mp3

Other    
http://www.somethinghitme.com/2013/11/13/snippets-i-always-forget-movement/

Fonts     
http://www.fontspace.com/category/video%20games?p=2

Dynamic JS Script loading      
http://www.html5rocks.com/en/tutorials/speed/script-loading/
