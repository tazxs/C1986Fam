Good afternoon, what is the C system ?, it is a system that takes the essence of multidimensionality into interpretation, the concept of dimension and the difference between the internal system and the dimension of the graphic foundations is completely erased, the opinion has been fundamentally developed that C cannot control the abstraction of the universe, but this is not so, looking at this piece of code:
section .text
     use16
     org  0x7C00  ;
start:
     mov  ax, cs
     mov  ds, ax  ;
 
     mov  si, message
     cld              ; 
     mov  ah, 0x0E    ;
     mov  bh, 0x00    ;
puts_loop:
     lodsb            ;
     test al, al      ;
     jz   puts_loop_exit
     int  0x10        ;
     jmp  puts_loop
puts_loop_exit:
     jmp  $           ; 
 
message:
     db   'Hello World!', 0
finish:
     times 0x1FE-finish+start db 0
     db   0x55, 0xAA  ; 
we understand that C has full access to function abstractions, and their further multiplication and recursion as an integer int object, but why is it even like that? Because the version control system of bit and size concepts is completely nested in the vacuole of the structure itself, and the deeper the system is written, the greater the difference between them.
