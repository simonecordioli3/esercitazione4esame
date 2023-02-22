CC=gcc
CFLAGS=-std=gnu99

all: local_minima most_frequent

local_minima: FORCE
	rm -rf *~ local_minima
	$(CC) -o local_minima local_minima.c local_minima_main.obj $(CFLAGS)

most_frequent: FORCE
	rm -rf *~ most_frequent
	$(CC) -o most_frequent most_frequent.c most_frequent_main.obj $(CFLAGS)

clean:
	rm -rf *~ local_minima most_frequent

FORCE: