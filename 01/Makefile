obj-m += hello.o
SRC := /lib/modules/$(shell uname -r)/build

all:
	make -C $(SRC) M=$(PWD) modules

clean:
	make -C $(SRC) M=$(PWD) clean
