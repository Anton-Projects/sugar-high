# sugar-high
Internship Selection Spring 2020 - problem solution

Step 1: creating a copy of the array given in order to work with the copy and keep the original one unchanged;
Step 2: Creating an empty array in which I will push the indices I take from the original array;
Step 3: Sorting the input array so that I can be sure it starts with the candies containing the fewest grams of sugar total. This way I will be able to take the maximum number of candies possible.
Step 4: Iterating over the sorted array of candies. I use the IF-oparator to select only the elements whose combined sugar content doesn't exceed the threshold left. I take their index in the input array and add it to the new array I have created (named candiesToEat). With every step I reduce the threshold by the quantity of sugar in every element I take.
Step 5: I log a sorted (ascending) array of indices of the candies that can be eaten;
