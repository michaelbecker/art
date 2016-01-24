all: hello_world hello_world.dis

hello_world:
	gcc hello_world.c -o hello_world

hello_world.dis: hello_world
	objdump -s -d hello_world > hello_world.dis

.PHONEY:.clean
clean:
	- rm hello_world hello_world.dis


