.PHONY: clean

all: pslib.a

pslib.a: pslib.c
	gcc -c -g -Wall -o pslib.o pslib.c
	ar rcs libps.a pslib.o

clean:
	rm -f *.o *.a
