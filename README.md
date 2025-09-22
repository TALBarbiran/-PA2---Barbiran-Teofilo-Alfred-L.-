# -PA2---Barbiran-Teofilo-Alfred-L.-

**FOR THE NORMALIZATION PROBLEM**
- Creating a random 5x5 array can be done by using the function "np.random.random()". It allows the user to input the dimensions required by the problem, which fills each element in the array with random numbers.
- Since normalization requires a formula, we have to define the variables that are needed to perform normalization. ".mean()" and ".std" are variables that return the mean and standard deviation of the array. By inputting the defined variables in a formula = Z, Z outputs the array in which each value is normalized.

**FOR THE DIVISIBLE BY 3 PROBLEM** 
- Use the "np.arange()" function to output an array of 1-100 integers. It allows the input of evenly spaced values from "1" to "101" with "1" in the end being the step value.
- To reshape it into a 10x10 array that outputs the square of the first 1-100 integers,  the ".reshape()" function allows the array to be manipulated while not changing data.
- In order to output the  values divisible by 3, define another array that uses a command that lists the values divisible by 3 with no remainder values. Hence, the "==0" syntax is used.
