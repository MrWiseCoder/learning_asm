
PRG=hello

all:
	gcc -c $(PRG).s -o $(PRG).o
	ld $(PRG).o -o $(PRG)

run:
	./$(PRG)

clean:
	rm *.o
	rm $(PRG)

