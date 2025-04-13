CC=gcc
CFLAGS=-Wall -Wextra -Werror 
LDFLAGS=-lX11 -lXft -lXcomposite


all: src/main.c
	$(CC) $(CFLAGS) -o main $? $(LDFLAGS)

clean:
	rm main
