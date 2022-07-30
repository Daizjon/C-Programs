CXX=		g++
CXXFLAGS=	-g -Wall -std=gnu++11
SHELL=		bash

all:		pgminfo neg bigwhite hflip

pgminfo:	pgminfo.cpp
	$(CXX) $(CXXFLAGS) -o $@ $^

bigwhite:	bigwhite.cpp
	$(CXX) $(CXXFLAGS) -o $@ $^

neg:	neg.cpp
	$(CXX) $(CXXFLAGS) -o $@ $^

hflip:	hflip.cpp
	$(CXX) $(CXXFLAGS) -o $@ $^

clean:
	rm -f pgminfo neg bigwhite hflip

test:		test-output 

test-output:	pgminfo neg hflip bigwhite
	@echo Testing output...
	@/home/jplank/cs140/Labs/Lab2/gradeall

