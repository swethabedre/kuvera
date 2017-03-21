# kuvera

Link to respository is 

Thought Process

Using NodeJS to solve the approach. We can use built in JavaScript object Math to generate a whole random number between 6 and 15.

Use Math.random(), which generates a random floating number between 0 and 1.
Multiply this number with difference of maximum and mininum number, so that you get a number which is less than 10 in this case.
Use Math.floor() to get a largest integer which is less than or equal to given floating number.
Finally add the minimum number of 6, so that the generated number is between 6 and 16 in above case. 
