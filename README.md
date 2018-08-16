# Notes-on-cpp-2d-game-engines


## Game programming / media and physics libraries in c++:


### Raylib:

To use without downloading an installer:

https://github.com/raysan5/raylib/tree/master/release 


raylib.dll includes all raylib modules except easings.h and physac.h there modules should be managed by user, include them in your project.


https://github.com/raysan5/raylib/tree/master/src

For visual studio see:

https://github.com/raysan5/raylib/wiki/Create-Visual-Studio-Project

and 

https://github.com/raysan5/raylib/tree/master/projects/VS2017

Also see:

https://github.com/raysan5/raylib/wiki


### SFML:

https://www.sfml-dev.org/download.php

also sometimes: 

https://nightlybuilds.ch/project/show/1/SFML/

and for physics I can use:

https://github.com/erincatto/Box2D

CMake can be used if not using visual studio:

https://github.com/SFML/SFML/wiki/Tutorial%3A-Build-your-SFML-project-with-CMake



### LoveLib:

Is the c++ version of Lua love 2d possibly:

https://bitbucket.org/rude/love/src

or most likely this:

https://bitbucket.org/rude/megasource/src