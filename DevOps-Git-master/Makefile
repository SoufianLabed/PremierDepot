enzyme: enzyme.c pathway.c main.c liste.c
	gcc -o $@ $^

liste.o: liste.c
enzyme.o: enzyme.c
pathway.o: pathway.c
main.o: main.c

clean:
	rm -f ~.o

mrproper: clean
	rm -f enzyme