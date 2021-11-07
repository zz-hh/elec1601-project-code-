# elec1601-project-code-M18_19

Software simulation code in software folder, another is code for the phycical robot.

Compile: gcc wall.c formulas.c robot.c main.c -o main $(pkg-config --cflags-only-I sdl2) $(pkg-config --libs-only-L sdl2) $(pkg-config --libs-only-l sdl2)
