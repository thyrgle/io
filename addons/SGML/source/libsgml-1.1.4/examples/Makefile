# Generated automatically from Makefile.in by configure.
CC=gcc

all:
	${CC} -I../include -Wall -O3 test.c -o test ../libsgml.a
	${CC} -I../include -Wall -O3 testhtml.c -o testhtml ../libsgml.a
	${CC} -I../include -Wall -O3 testxml.c -o testxml ../libsgml.a
	${CC} -I../include -Wall -O3 variant.c -o variant ../libsgml.a

clean:
	rm -f testhtml testxml test variant

distclean:
	make clean
	rm -f Makefile
