# Lab Assignment 2

In this assignment you are required to write a program that reads an array of
integers from file and computes its mean and median.

# Notes & Considerations

• File that you are going to read can have any(including 0) number of integers. So,
you are advised to read the file twice: once for determining its length, once for
actually reading the integers.

• You can use the executable we provided to generate an array.

```
./array_gen 10000 arr_file [upper_bound]
```

will create a file named arr_file and put 10000 integers in it, separated by newline
characters. Optional upper_bound argument allows you to define an upper bound to the
random integers that are going to be created. If you omit the argument, it defaults to
INT_MAX. 

HINT: You can use very small arrays with very small integers as a toy input
to debug your code.

• You can use the executable we provided to find the mean and median and
compare your results.

```
./mean_median arr_file
```

will compute the mean and median of the file and output the results.

# Requirements
• You have to use dynamic memory allocation/deallocation. Namely; calloc() and
free() functions.
• You have to sort the array, with the Selection Sort algorithm you learned in the
lecture to find the median.