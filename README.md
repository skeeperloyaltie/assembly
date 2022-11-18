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
      07 represents the low order bytes while 25 represents the high order bytes so 

    25 will be placed on the left  side of the memory basically taken from the register
    07 will be placed on the right side of the memory basically taken from the register
 


  The processor reads the instruction from the memory based on th following:
    - Absolute addressing - a direct reference to a specific memory location 
    - Segment addressing - starting address of a memory segment with the offset value
      - Ofset value - The distance in bytes from the segment addess to another location within the segment  ( a displacement )

### Syntax 

