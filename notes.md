# What is a Computer?

-Best Answer: A computer is a "Turing Machine".

# What is a "Turing Machine"?

-A "Turing Machine" is a device created by Alan Turing that can complete
operations or calculations.
-It features a "Turing tape" which can be read by and written
on with the machine.
-The tape is divided into "cells".
-Each "cell" contains a symbol and a finite number.
-These machines can complete all calculations that are "computable".

# What is "Turing Complete"?

-A programming language is considered "Turing complete" if it has
conditional branching (i.e. - if/else statements) and can store variables
in memory.

-16 GB of RAM (memory) = 16 billion small cells (bytes) of memory storage
-2.2 Ghz processing speed = 2.2 billion operations/second

# How much memory does an array take up in memory?

-memory storage for an array = 4 bytes (integer) + 4 bytes (integer) + 8 bytes (pointer)
-memory storage for an array = ~4 billion bits

# Steps to Storing Information in an Array

1. Allocate memory, for the array, ahead of time
2. Point to the array

# To Access an Index in The Array

1. index \* sizeof(type) + start_address

# NEVER create a string using a FOR loop

-It is extremely slow.
-ALWAYS build arrays from the back.
