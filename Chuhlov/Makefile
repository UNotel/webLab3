all: printINT

printINT: main.o script.o
	gcc -o printINT main.o script.o

main.o: main.c
	gcc -c main.c

script.o: script.c
	gcc -c script.c

start:
	./printINT

build:
	cp printINT /home/vadim/Labs/webLabs/Builds

clean:
	rm -rf *.o printINT

clear:
	rm -rf printINT
