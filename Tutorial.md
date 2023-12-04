# How To: Binary
-In this tutorial we will learn how to convert binary to numbers.

## Binary to Numbers


#### Ex. 00010010

-This is what is called a byte. This will eventually represent our number.
-A byte is made up of 8 numbers called bits.
-A bit can either be a 0 or a 1 meaning "False" or True"

These 8 digits all have a specified number that corresponds to their placement in the line. 

From right to left the corresponding number is in base 2.

- 1st = 1
- 2nd = 2
- 3rd = 4
- 4th = 8
- 5th = 16
- 6th = 32
- 7th = 64
- 8th = 128


So let's go back to our example:

#### Ex. 00010010

- As we can see the 2nd bit is turned on as well as the 5th.
- If we go back to the graphic above we can see that the number 2 is in the 2nd spot
and the number 16 is in the 5th spot.
- So what we have to do is add all numbers that are "On" together to get our result.
- In this case the number would be 18 because 16 + 2 = 18.

## Recap with new Example

Ex. 01100111

### Step 1: Analyze what bits are turned on
- We can see that the number 1,2,3,6 and 7 bits are turned on

### Step 2: Find what numbers corrolate to those bits
- 1 = 1
- 2 = 2
- 3 = 4
- 6 = 32
- 7 = 64
### Step 3: Add all of the numbers together

1 + 2 + 4 + 32 + 64 = 103
