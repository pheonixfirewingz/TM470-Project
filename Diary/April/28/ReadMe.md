\# Game Choice



I had to look through several open-source games on GitHub as the ones I looked at initially had already been ported to the web, I eventually found a game called OpenLoco which has not yet received a web port and so I have decided to use this for my project. This took longer than anticipated as some games did not already have a web port but were written in a language not compatible with a web port.



\# Initial Environment Setup



In order to port my chosen game to the web I have to use a specialised compiler, called Emscripten. This requires setting up, especially when using a Linux setup where the terminal is required for this setup. I chose Linux over Windows because the compiler is designed for Linux first with a Windows port. Despite the difficulties in doing this, it would have been a bigger challenge to do on Windows. When it comes to porting the game, I will have to figure out how to point CMake to use Emscripten rather than the Linux system default of Gcc.

