#### Double On Overflow
- 1st range is single byte 0x00-0xFE (0-254). 0xFF is **signal** to read next 2 bytes in network byte order (big endian)
- 2nd range is then 2 bytes 0x0000 - 0xFFFE . 
ABCDEF
