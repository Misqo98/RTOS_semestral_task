CC=gcc
CFLAGS= -lrt -lpthread

client: mclient1.c
	$(CC) mclient1.c -o mclient1 $(CFLAGS)
server: mserver1.c
	$(CC) mserver1.c -o mserver1 $(CFLAGS)

clean: mserver1 mclient1
	rm mserver1
	rm mclient1
