# Generated from Makefile.in, do not edit
CC=cc
CFLAGS= -g -I../../include -Wall
LIBS=  -L../.. -lcrypto
EXAMPLES=sign

all: $(EXAMPLES) 

sign: sign.o
	$(CC) -o sign sign.o $(LIBS)

clean:	
	rm -f $(EXAMPLES) *.o

test: all
	./sign
# DO NOT DELETE THIS LINE -- make depend depends on it.
