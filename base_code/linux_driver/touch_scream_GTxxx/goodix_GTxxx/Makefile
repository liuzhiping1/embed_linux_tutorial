#KERNEL_DIR = /home/new_kernel2/ebf-buster-linux
KERNEL_DIR = /home/gulun/fire/kernel/ebf-buster-linux

obj-m := goodix_gtxxx.o

all:
	$(MAKE) EXTRA_CFLAGS=-fno-pic -C $(KERNEL_DIR) M=$(CURDIR) modules
	
.PHONY:clean
clean:
	$(MAKE)  -C $(KERNEL_DIR) M=$(CURDIR) clean
