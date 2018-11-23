## Disclaimer!

**Due to academic Policy, I am not allowed to share the code online and will have to share code through email or other methods.**

This project was done under the course CMPSC 311 at Penn State Main Campus.

**CMPSC 311 Course Description**: Introduction to Systems Programming.

# What is CRUD/HDD?

CRUD is an acroynm for "Create, Remove, Update, and Delete".

HDD is an acroynm for "Hard disk drive"

The project uses the model/idea of a block storage device and asks for implementation of coded functions that mimics standard C file commands (open, close, read, write, and seek). In addition to these functions, the application was later expanded to support saving, loading, and deleting states of the HDD device. As an example, the program would be able to load in blocks of data from a previous saved state. As a final improvement to the project, I implemented network code that allowed communication between a client and server where I would be capable to send message across the server and receive a reponse back from the server

As an example of one of the application's function: The program was capable of reading various text files into the program’s allocated block memory and writing it to a separate text file. It would also be capable to compare and contrast 2 text files to see if they contained the same exact text data. 

What was impressively stressed in this project: 
 - Memory allocation
 - Documentation
 - Clean Code
 - Usage of Helper functions
 
 


## What was in the block of data?

<img src="Images/Image2.png" width="700">

The ordering convention of memory used in the block of data was Big Endian.

The 64-bit block stressed proper allocation of bytes location as listed in the picture above.



## How does this work?

**_For a more in-depth description of the application and what I needed to do, please look at the assignment PDFs_**

<img src="Images/Image1.png" width="500">

The device already had its own pre-defined set of functions that allowed communication with the HDD-device. My code implelmented the communication of information to the external block storage device like a hard driver (HDD)






## Documentation 

Each function is documented in this style and contained concise, but clear details pertaining about the function's purpose and what it did.
```
////////////////////////////////////////////////////////////////////////////////
//// Function     : ????
// Description  : ????
//
// Inputs       : ????
// Outputs      : ????
//
```
### Software used

VM-ware: Linux 64 bit


## Authors

Me: Danny Zhu

Stressed properly memory management and 



## Important Concepts from Class utilized in this Project.

## Project Background

** **CRUD stands for Create, Remove, Update, and Delete.**

Sophomore Year: I utilized C programming within a virtual machine UNIX enviroment and implemented a CRUD device using Linux tools and C code. The CRUD device stressed proper memory allocation for each byte of information and utilized Network programming to communicate information between a client and server. 
