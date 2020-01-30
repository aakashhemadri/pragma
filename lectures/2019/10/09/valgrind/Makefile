C = gcc
# -ggdb compiler option creates a gdb friendly binary that will givbree us more information during debugging!
FLAGS = -ggdb -Wall -std=c11 

main: test.c # Fun Fact g++ recognizes .cc, .cpp, .cxx, .C, .CPP, .cp, c++ has valid c++ files :)
	${C} ${FLAGS} -o test.out test.c
	@echo -e "\nCompilation done.\n"

clean:
	rm -f test.out