CFLAGS := -O0
CFLAGS += -g
CFLAGS += -Wall
CFLAGS += -Wextra
#CFLAGS += -s

cu: *.c
	gcc $(CFLAGS) *.c -o cu -levent

.PHONY: clean
clean:
	rm -vf cu
