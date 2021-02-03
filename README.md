# linuxCut
C implementation of the Linux "cut" command. This program identifies and cuts specified fields using given command line arguments. 

The command line argument limitations are as follows:
- There can only be positive unique fields specified in increasing order.
- There must be at least one, at most 100, given fields.
- Input and output delimeters must be a single character.

## How to Run
1. Compile assign2.c assign2funcs.c
2. Call *./a.out **[input delimeter] [output delimeter] [fields]** <input*
3. **Note:** Check if output are the same using the linux cut command with the same arguments!

## Acknowledgements
- Project assigned by Dr. Woit at Ryerson University
- Collaborated with Ralph and Georgz 
