main: main.o
	gcc -L/opt/local/lib -Wall -o main main.o -lSDL2 -lSDL2_image

main.o: main.c
	gcc -Wall -std=c99 -c main.c