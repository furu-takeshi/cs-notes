# Data Representation
## Basic Units of Data
Unit|Size
-|-
Bit (b)|Binary Digit (0 or 1) - The smallest unit of data.
Nibble|4 bits
Byte (B)|8 bits
Kilobyte(KB)|1024 Bytes (2<sup>10</sup>)
Megabyte (MB)|1024KB (2<sup>20</sup>)
Gigabyte (GB)|1024MB (2<sup>30</sup>)

## Number Systems
Computers use various number systems:

System|Base|Digits Used|Examples
-|-|-|-
Decimal|10|0, 1, 2, 3, 4, 5, 6, 7, 8, 9|(123)<sub>10</sub>
Binary|2|0,1|(111011)<sub>2</sub>​
Octal|8|1,2,3,4,5,6,7|(173)<sub>8</sub>
Hexadecimal|16|0-9, A-F (A=10, F=15)|(7B)<sub>16</sub>

## Key Conversions
* **Binary to Decimal**: Sum of (Digit * Base^Position).
    * *Example*: (1011)<sub>2</sub> = (1 * 2<sup>3</sup>) + (0 * 2<sup>2</sup>) + (1 * 2<sup>1</sup>) + (1 * 2<sup>0</sup>) = 8 + 0 + 2 + 1 = (11)<sub>10</sub>

* **Decimal to Binary**: Repeated Division by 2. Collect the remainders from bottom to top.

## Character Encoding
Used to represent characters (letters, numbers, symbols) as binary codes.
* **ASCII:** Uses 7 or 8 bits; limited to English characters.
* **Unicode:** Uses 16 or 32 bits; can represent characters from almost all languages worldwide.
