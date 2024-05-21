# Makefile para compilar y ejecutar hello.c

CC = gcc
CFLAGS = -std=c18 -Wall -Wextra -Werror -pedantic 
PROG = hello.c
OBJ = hello.o

.PHONY: all clean

all: hello

hello: hello.o
	$(CC) $(CFLAGS) -o hello $(OBJ)

hello.o: hello.c
	$(CC) $(CFLAGS) -c $(PROG)

clean:
	rm -f hello $(OBJ)

archivo_texto: hello.exe
	./hello.exe > hello.txt