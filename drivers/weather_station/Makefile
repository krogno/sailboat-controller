
all:
	#--- COMPILING [U200] FOR x86 ---#
	gcc -Wall u200.c -o ./bin/u200_x86
	#--- COMPILING [U200] FOR ARM ---#
	arm-linux-gnueabi-gcc -Wall u200.c -o ./bin/u200_arm
	scp ./bin/u200_arm root@10.42.0.32:/home/root
