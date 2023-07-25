hello: hello.o
	ld hello.o -o hello
hello.o: hello.asm
	nasm -f elf64 -o hello.o hello.asm	
hello.asm:
	echo "section .data" > hello.asm

clean:
	rm hello.o
	rm hello