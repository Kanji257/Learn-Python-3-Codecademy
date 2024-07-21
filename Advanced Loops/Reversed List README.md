For the final challenge, we are going to test two lists to see if the second list is the reverse of the first list. There are a few different ways to approach this, but we are going to try a #method that iterates through each of the values in one direction for the first list and compares them against the values starting from the other direction in the second list. Here is what you #need to do:

Define a function that has two input parameters for our lists

Loop through every index in one of the lists from beginning to end

Within the loop, compare the element in the first list at the current index against the element at the second list’s last index minus the current index. If there was a mismatch, then the lists aren’t reversed and we can return False

If the loop ended successfully, then we know the lists are reversed and we can return True.