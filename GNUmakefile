FLAGS := -O0
FLAGS += -g
FLAGS += -Wall
FLAGS += -Wextra
FLAGS += -Wno-unused-parameter
#FLAGS += -Wno-pointer-sign
FLAGS += -Wno-implicit-fallthrough
#FLAGS += -s
FLAGS += -D_GNU_SOURCE
FLAGS += $(shell pkg-config --cflags --libs libbsd-overlay libevent)

cu: *.c
	gcc $(FLAGS) *.c -o cu

.PHONY: clean
clean:
	rm -vf cu

cu: GNUmakefile
