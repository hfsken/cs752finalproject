CXX = g++
CC = gcc
CFLAGS = -Wall
DEP = ../lib/dpc2sim.a

all: bestoffset lookahead

bestoffset: dpc2_bestoffset.c
	$(CC) -o $@ $< $(DEP) $(CFLAGS)
lookahead: dpc2_lookahead.cpp
	$(CXX) -o $@ $< $(DEP) $(CFLAGS)
