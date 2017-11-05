DIROBJ := obj/
DIREXE := exec/
DIRHEA := include/
DIRSRC := src/

CFLAGS := -I$(DIRHEA) -c -Wall -ansi
LDFLAGS := -lglut -lGLU -lGL
CC := gcc

all: dirs practica_1

dirs:
	mkdir -p $(DIROBJ) $(DIREXE)

practica_1: $(DIROBJ)practica_1.o 
	$(CC) -o $(DIREXE)$@ $^ $(LDFLAGS)

clean: 
	rm -rf *~ core $(DIROBJ) $(DIREXE) $(DIRHEA)*~ $(DIRSRC)*~
