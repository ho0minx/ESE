CC = gcc
CFLAGS += -g
OBJ = main.o read.o write.o

test : ${OBJ)
	$(CC) -o $@ $^
main.o : io.h main.c
	gcc -c main.c
read.o : io.h read.c
	gcc -c read.c
wirte.o : io.h write.c
	gcc -c write.c
clean :
	rm -rf *.o
