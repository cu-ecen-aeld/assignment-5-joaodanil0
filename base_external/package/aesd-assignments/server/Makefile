
default: aesdsocket
all: aesdsocket


aesdsocket: aesdsocket.o 
	$(CC) $(LDFLAGS) -o aesdsocket aesdsocket.o

aesdsocket.o: aesdsocket.c
	$(CC) $(CCFLAGS) -c aesdsocket.c

clean:
	rm -rf *.o
	rm aesdsocket