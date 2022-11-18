### Assembly NASM 
- DATA SIZES
  - word - 2 byte data item 
  - Double word - 4byte (32 bit ) data item 
  - Quadword - 8-byte Data type (64 bits)
  - Paragraph - 16 byte 128 bits area
  - Kilobyte 1024 bytes 
  - Megabyte - 1048576 bytes

- Binary Systems 
  - One's Complement
  - Two's Complement 

- Hexadecimal Number Systems
  - To check ()

  -- Arithmetics 
    - Binary 
    - 

### Addressing in Memory 

- STEPS
  - Fetch ( from from memory - Instruction ) 
  - DEcode the inststruction 
  - Execute Instruction 


  Basically the processor stores the bytes in reverse order
  - The lower order will be moved to the lower memory address while the high order bytes will be stored in the high memory location

  EXample: 
    - 0725H
    - 07 represents the low order bytes while 25 represents the high order bytes so 

    25 will be placed on the left  side of the memory basically taken from the register
    07 will be placed on the right side of the memory basically taken from the register
 


  The processor reads the instruction from the memory based on th following:
    - Absolute addressing - a direct reference to a specific memory location 
    - Segment addressing - starting address of a memory segment with the offset value
      - Ofset value - The distance in bytes from the segment addess to another location within the segment  ( a displacement )

### Language Statements
  - Executable Instructions  - Tells the processor what to do [ Consists of an OPCODE - Generates one machine language instruction ]
  - Assembler directives or pseudo-ops - Tells the assembler about the various aspects of the assembly process - Non executable
  - Macros - Text substitution mechanisms



### Compiling and Linking an Assembly Program in NASM
- Make sure you have set the path of nasm and ld binaries in your PATH environment variable. Now, take the following steps for compiling and linking the above program −

  - Type the above code using a text editor and save it as hello.asm.

  - Make sure that you are in the same directory as where you saved hello.asm.

  - To assemble the program, type nasm -f elf hello.asm

  - If there is any error, you will be prompted about that at this stage. Otherwise, an object file of your program named hello.o will be created.

  - To link the object file and create an executable file named hello, type ld -m elf_i386 -s -o hello hello.o

  - Execute the program by typing ./hello

If you have done everything correctly, it will display 'Hello, world!' on the screen.