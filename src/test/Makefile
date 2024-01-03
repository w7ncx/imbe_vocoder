CXX     := g++
CFLAGS  := -O2 -Wall -I../lib
LDFLAGS :=
LIBS    := 

OBJECTS = speed.o ../lib/imbe.a

.PHONY: all
all:		speed

speed:	$(OBJECTS)
		$(CXX) -o speed $(LDFLAGS) $(LIBS) $(OBJECTS)

%.o: %.cpp
		$(CXX) $(CFLAGS) -c -o $@ $<

