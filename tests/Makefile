CC = msp430-elf-gcc

test0: CFLAGS += -mmcu=msp430f6747
#test0: CFLAGS += -mmcu=msp430f2001
test1: CFLAGS += -mmcu=msp430f2001

CFLAGS += -Os

all: test0 test1

clean:
	rm -f test0 test1

