TARGETS = fib fib_fast

CXX = g++
CPPFLAGS = -std=c++17 -O3
LDLIBS=-lm

all: $(TARGETS)

fib: fib.cpp
	$(CXX) $(CPPFLAGS) $< -o $@

fib_fast: fib.cpp
	$(CXX) $(CPPFLAGS) -DFAST $< -o $@

clean:
	$(RM) $(TARGETS)

.PHONY: all clean