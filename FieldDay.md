# Field Day

## Description
> This challenge required us to decode FIELDATA to get our flag. There was a sequence of 28 binary strings, each 12 bits long, representing holes on an 80-column punch
> card using the FIELDATA (UNIVAC) character encoding system. 

## My Solve

This is how the 12 bit string is indexed :
12 11 0 1 2 3 4 5 6 7 8 9

Each FIELDATA character (like A,B,1,2..) is represented by a combination of those bits.
Basically, every time the bit value is equal to 1, its bit position is considered.

So when you see: 010000010010, according to the indexing system, this means 11-5 which means N.
<img width="189" height="847" alt="image" src="https://github.com/user-attachments/assets/d7995af8-f062-4376-b1fa-9679e8e432ea" />

 
