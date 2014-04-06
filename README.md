# LC3Program #
---

## How to run ##

1. Download & install the [LC3 Simulator](http://highered.mcgraw-hill.com/sites/dl/free/0072467509/104652/LC301.exe "LC3 Simulator").
2. Open the binary file in **LCEdit** and convert to base 2. This will create an object file.
3. Load the object file in **Simulate** and run the program. 

## What it does ##

- This program calculates 2<sup>**n**</sup>, where the user enters **n**. 
- **n** can be any value from 01 to 53.
-  It resets the state of the registers and stack each time it runs.

## History ##

- I was originally given this assignment in 2010, while studying [Computer Systems 1](https://www.cs.auckland.ac.nz/courses/compsci210s1c/ "Computer Systems 1") at [The University of Auckland](https://www.cs.auckland.ac.nz/ "The University of Auckland").

- This assignment was memorable for how I misunderstood the requirements and wrote it in binary. I ended up learning the hard way to pay attention in class. If you've learnt Assembly you'll find most people write code in a human readable format, for example:

	`ADD R2, R3, R4	;R2 <- R3 + R4`

	Where as I would have written:

	`0001 010 011 000 100	;R2 <- R3 + R4`

- I had all of the assignment requirements completed about 6 hours before it was due. This included having it work for **n**>15, for extra credit. But I talked to the lecturer in the hallway about adding new features, and he said they were required. It turns out they weren't, but I still ended up submitting a broken piece of code. I ended up learning the hard way I needed to read assignments very carefully.

- I learnt a lot from this project. Because of my backwards approach I was forced to learn a lot more about how Assembly works, and I really enjoy working on low-level code now. I also learnt about other things they don't teach in unversity - like the value of source control and understanding requirements.