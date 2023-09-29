CFLAGS = -c -I$(HOME)/Programming/include

LFLAGS = -L$(HOME)/Programming/lib

LIBS = -ldataStructures

project2: project2.o
	g++ $(LFLAGS) -o project2 project2.o $(LIBS)
	
project2.o: project2.cc
	g++ $(CFLAGS) project2.cc

clean:
	rm *.o project2

