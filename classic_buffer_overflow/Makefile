CC=gcc
CFLAGS=-I.  -g -zexecstack -fno-stack-protector

vulnerable: vulnerable.o
	$(CC) -o vulnerable vulnerable.o $(CFLAGS)

clean:
	rm -rf vulnerable.o
	rm -rf vulnerable

