## Ricardo Rosa

### ISTA220 Homework 16

### C# 


***Read chapter 16, pages 329 – 352 in the C# Step by Step book.***

##### 1. Give five examples (using valid C# code) of the five bitwise operators listed in the text.
1 OR
& and
~ NOT
<< >> Shift
^ XOR



##### 2. Does C# implement the right-shift (>>) operator? If so, give an example of its operation using valie C# code.
Yes.

##### 3. Explain in detail this code: bits & (1 << index);.
1 is shifted by index = result
bits & result = 1 if both are true (1 & 1= 1)

##### 4. Explain in detail this code: bits |= (1 << index);.
1 is shifted by index = result
bit at index is evaluated to true regardless of its first state

##### 5. Explain in detail this code: bits &= (1 << index);.

1 is shifted by index = result
bits & result = true if both bits and result are true

##### 6. How does C# interpret this? bool peek = bits[n];


##### 7. How does C# interpret this? bits[n] = true;


##### 8. How does C# interpret this? bits[n] ^= true;


##### 9. Assume that users were assigned read, write, and execute permissions according to this scheme: read = 1, write = 2, execute = 4. How would you interpret the following user permissions:
(a) permission = 0 none

(b) permission = 1 read

(c) permission = 2 write

(d) permission = 3 read and write

(e) permission = 4 execute

(f) permission = 5 execute and read

(g) permission = 6 execute and write

(h) permission = 7 execute, write and read

##### 10. Answer the previous question by converting the decimal permissions into binary permissions. What does this tell you about using this shceme of permissions?