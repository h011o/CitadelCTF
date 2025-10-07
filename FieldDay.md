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
!(https://media.discordapp.net/attachments/1420063876057399306/1425007844046012549/image.png?ex=68e60579&is=68e4b3f9&hm=00f7b2e9861ab84c86042c1d3041c2e4c79e09cde8e70fab75b674d236d68131&=&format=webp&quality=lossless&width=221&height=989)

 
