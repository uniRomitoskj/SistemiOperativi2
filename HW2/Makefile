all: client.c server.c
	gcc client.c -o client
	gcc -pthread server.c -o server

.PHONY: clean

clean:
	rm -f log.txt
