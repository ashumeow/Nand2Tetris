Assembler 
```
=> software
=> first software layer above the hardware
```
Cycle:
```
Assembly language program => Assembler (PC) => Machine language program => HACK computer
```
Basic Assembler Logic:
```
Repeat:
1. Read the next assembly language command.
2. Break it into the different fields it's composed of.
3. Lookup the binary code for each field.
4. Combine these codes into a single machine language command.
5. Output this machine language command.
Until end-of-file reached
```
Explaining the logic:
```
1. Read the next assembly language command.
-- Ignore the whitespace
-- Load R1, 18 // Read this into an array of characters

2. Break it into the different fields it's composed of.
-- Taking the string of characters and break it into parts
-- Involves string manipulation.
```
![](http://geekresearchlab.net/coursera/n2t/asm-1.jpg)
```
3. Lookup the binary code for each field.
-- basic translation of each input.
```
![](http://geekresearchlab.net/coursera/n2t/asm-2.jpg)
```
4. Combine these codes into a single machine language command.
-- Put the translation of each input and combine them together.

5. Output this machine language command.
-- print the output
```
![](http://geekresearchlab.net/coursera/n2t/asm-1.jpg)
