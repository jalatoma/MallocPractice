# Malloc Practice
Project 5 in CSCI 2021 (UMN) completed in Fall 2021. Main purpose was to practice the malloc() function in C.

In this project, you will implement a simple memory allocator built around doubly-linked lists. This exercise is related to some of the final topics covered in lecture and will also give you greater insight into how the C library functions malloc and free work as well as why frequent allocation is generally slow and can degrade the performance of your code.

"EL Malloc" implements a simple, explicit list memory allocator. This manages heap memory in doubly-linked lists of Available and Used memory blocks to provide the functions el_malloc() and el_free() to its users. It could be extended with some work to be a drop-in replacement for the original malloc() and free() functions.

***I only edited and el_malloc.c***
