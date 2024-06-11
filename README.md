readme

This Java code demonstrates a method to perform left rotation on an integer array.

Variables
a: An integer array representing the array to rotate.
d: An integer representing the number of left rotations to perform.
rotatedArray: An integer array representing the rotated array ‘a’

Algorithm
First: we got the length of the array and stored it in the vaiable 'n'.
We then used the value stored in the variable 'n' to create a new array called 'rotatedArray' with the same length as the array 'a' so as to store the new rotated array 'a'.

Secondly: we then used a for loop to iterate over each  element of the array 'a'.
Inside the loop, the new index for each element after rotation is calculated using the formula (i + (n - d)) % n, where ‘i’ is the current index, ‘n’ is the length of the array, and ‘d’ is the number of left rotations. The element at the current index of the input array a is assigned to the calculated new index in the rotatedArray.

Thirdly: After all elements have been rotated and assigned to the new array, the rotatedArray is returned as the result


