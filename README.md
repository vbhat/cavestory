# cavestory

Run this command to compile

g++ main.cpp graphics.cpp game.cpp input.cpp -I/usr/local/include -L/usr/local/lib -lSDL2 -o main

g++ main.cpp graphics.cpp game.cpp input.cpp sprite.cpp -I /Library/Frameworks/SDL2.framework/Headers -I /Library/Frameworks/SDL2_image.framework/Headers -F /Library/Frameworks/ -framework SDL2 -framework SDL2_image -o main