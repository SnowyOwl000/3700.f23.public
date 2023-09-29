CFLAGS = -c -I$(HOME)/Programming/include

OBJS = fraction.o

libdataStructures.a: $(OBJS)
	ar r libdataStructures.a $(OBJS)
	ranlib libdataStructures.a

fraction.o: ../src/fraction.cc ../include/fraction.h
	g++ $(CFLAGS) -o fraction.o ../src/fraction.cc

