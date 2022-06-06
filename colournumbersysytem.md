#NUMBER SYSTEM TO GENERATE COLOURS

1. Binary Number System:

binary   = 2 digits
Base     =  2
Numerals = 0,1
For this numbers system, the two digits are 0 and 1.
0  = false,no
1  = true,yes

Unit's place     = ^0
Tens's place     = ^1
Hundred's place  = ^2
Thousand's place = ^3
And so on..........

# Convert Binary Numbers To Decimal Number

01 = 0 * 2^1 + 1 * 2^0
   = 0 * 2   + 1 * 1
   = 0       + 1
   = 1

1010 = 1 * 2^3 + 0 * 2^2 + 1 * 2^1 + 0 * 2^0
     = 1 * 8   + 0 * 4   + 1 * 2   + 0 * 1
     = 8 + 0 + 2 + 0
     = 10

101101 = 1 * 2^5 + 0 * 2^4 + 1 * 2^3 + 1* 2^2 + 0* 2^1 + 1* 2^0
       = 1 * 32  + 0 * 16  + 1 * 8 + 1 * 4    + 0 * 2  + 1* 1
       = 32 + 0 + 8 + 4 + 0 + 1
       = 45
 



2. Decimal Number System:

Decimal   = 10 digits
Base      = 10
Numerals  = 0,1,2,3,4,5,6,7,8,9

EXAMPLE:

25890, 19934, 12345, 45678, 1234567, 47847567564848764

3. Hexadecimal Number System:

Hexadecimal   = 16 digits
Base     =  16
Numerals = 0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F

A = 10
B = 11
C = 12
D = 13
E = 14
F = 15

Unit's place     = ^0
Tens's place     = ^1
Hundred's place  = ^2
Thousand's place = ^3
And so on..........


# Convert Hexadecimal numbers into Decimal Nos
F => here F is a single digit hexadecimal number that means F is at UNITS place
F = F  * 16^0 
  = 15 * 1
  = 15

AE => here AE is a double digit hexadecimal number that means E is at UNITS place and A is at TENS place
AE = A  *  16^1  + E * 16^0
   = 10 * 16^1   + 14 * 16^0
   = 10 * 16     + 14 * 1
   = 160 + 14
   = 174

1CB46 => here 1CB46 is a 5 digit hexadecimal number that means 6 is at UNITS place , 4 is at TENS place, B is at HUNDREDS place, C is at THOUSANDS and 1 is at TEN THOUSANDS place.
1CB46 = 1 * 16^4   + C  * 16^3 + B  * 16^2 + 4 * 16^1 + 6 * 16^0
      = 1 * 65536  + 12 * 4096 + 11 * 256  + 4 * 16   + 6 * 1
      = 65536      + 49152     + 2816      + 64       + 6
      =117574

57AB3 = 5 * 16^4  + 7 * 16^3 + A * 16^2 + B * 16^1 + 3 * 16^0
      = 5 * 65536 + 7 * 4096 + 10 * 256 + 11 * 16 + 3* 1
      = 327680 +  28672 + 2560 + 176 + 3
      =  359046


00 = 0 * 16^1 + 0 * 16^0
   = 0 + 0
   = 0

000000 = 000

ff =  f  * 16^1 + f  * 16^0
   =  15 * 16   + 15 * 1
   =  240       + 15
   =  255

ffffff= 255 + 255 + 255
      = 765

#

=> Hexadecimal numbers are used to generate different shades and tints of colors in compute programming.

=> The color codes starts with "#" symbols followed by 6 characters.That means, there are 3 pairs   of 2 charachters each.

=> Each pair represents a different color.

a. The FIRST  pair represents RED
b. The SECOND pair represents GREEN
c. The THIRD  pair represents BLUE

=> Each character in the pair represents the amount of color

=. In computer programming the amonunt of color ranges from 0 to 255(that means there are 256 levels of amount).

#000000 = BLACK
#ffffff = WHITE
#808080 = GREY 
50% of red   = 128
50% of green = 128
50% of blue  = 128

# Convert Decimal To Hexadecimal No. 
128 =  128/16 = Q - 8, R - 0
    =    8/16 = Q - 0, R - 8
    = 80
To create the decimal nnumber we have to reverese combine the remainders 