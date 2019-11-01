1. Type the code and save it as hello.asm
2. Make sure that you are in the same directory as where you saved hello.asm
3. To assmeble the program, type nasm -f elf hello.asm
4. Then the hello.o will be created
5. type ld -m elf_i386 -s -o hello hello.o
6. ./hello

