# What is Time Complexity?

Time complexity represents the amount of time an algorithm takes to run as a function of the length of the input.

Time complexity provides an upper bound on the running time, helping us understand the worst-case scenario in terms of performance.

Time complexity is useful because it'll help us find out which solutions are the faster one. 

# Fastest to Slowest

# O(1) - Constant Time 
____
Time taken remains constant regardless of input size. It could be a million inputs and the time taken will be the same.

For all inputs to our algorithm there is and will always be only one operation required 

Examples:

Accessing an element in an array by index

Gauss's Trick: Take the last element of a array: [lastItem * (lastItem + 1) / 2] O(1)



# O(log(N)) - Logarithmic Time 
____________________________

log(N) grows VERY slowly. log(1,000,000) is only about 20. 

As you loop your operations are halved.

Divide and Conquer Algorithms. 

Can be efficient with large amounts of inputs/

Binary search in a sorted array


# O(N) - Linear 

Linear time typically means looping through a linear data structure a constant number of times.

For all inputs to our algorithm there will be one operation PER input, as the number of inputs scale, the number of operations scale with it 1:1.

Useful with small stuff

Finding an item in an unsorted list 

# O(N log N) - Linearithmic

Merge sort of quicksort


# O(N^2) - Quadratic Time 

Bubble sort or selection sort

# O(2 ^N) - Exponential Time

Finding all subsets of a set



# O(N!)-Factorial 

Solving the traveling salesman problem exhaustively







#SWE 