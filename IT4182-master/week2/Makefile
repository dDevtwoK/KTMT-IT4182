all: scanner
scanner: scanner.o token.o error.o charcode.o reader.o
	gcc scanner.o token.o error.o charcode.o reader.o -o all
scanner.o: scanner.c
	gcc -c scanner.c
token.o: token.c
	gcc -c token.c
reader.o: reader.c
	gcc -c reader.c
error.o: error.c
	gcc -c error.c
charcode.o: charcode.c
	gcc -c charcode.c
clean: 
	rm -f *.o *~
