obj-m:= mjmn.o

KERN_DIR = /lib/modules/$(shell uname -r)/build

PWD := $(shell pwd)

default	:
	$(MAKE) -C $(KERN_DIR) M=$(PWD) modules

clean	:
	$(MAKE) -C $(KERN_DIR) M=$(PWD) clean
