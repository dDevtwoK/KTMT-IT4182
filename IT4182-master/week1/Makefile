all: index
index: index.o stringhandle.o
		gcc index.o stringhandle.o -o all 
index.o: index.c
		gcc -c index.c
stringhandle.o: stringhandle.c
		gcc -c stringhandle.c	
clean:	
		rm -f *.o *~
