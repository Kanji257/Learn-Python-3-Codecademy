In this challenge, we need to find the indices in two equally sized lists where the numbers match. We will be iterating through both of them at the same time and comparing the values, if the #numbers are equal, then we record the index. These are the steps we need to accomplish this:

Define our function to accept two lists of numbers

Create a new list to store our matching indices

Loop through each index to the end of either of our lists

Within the loop, check if our first list at the current index is equal to the second list at the current index. If so, append the index where they matched

Return our list of indices