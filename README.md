PA #2

Nathan Josh Cacho

Normalization Problem

For this task, I had to create a random 5 x 5 ndarray using NumPy. I used np.random.rand() to generate random numbers between 0 and 1, and stored them in a variable called x.
To normalize the data, I calculated the mean with x.mean() and the standard deviation with x.std(). Then I applied the normalization formula.
This step made sure the data was centered around zero and scaled properly. After normalization, I saved the result into a file named x_normalized.npy using np.save()

Divisible by 3 Problem

For the second task, I needed to create a 10 x 10 ndarray made up of the squares of the first 100 positive integers. 
I used np.arange(1, 101)**2 to generate the squares, and then reshaped it into a 10 x 10 array with .reshape(10,10).
The problem asked me to find all numbers in the array that are divisible by 3. I managed to do that using numpy's modulo operation: A[A % 3 == 0]. 
This filtered out only the elements that were divisible by 3. Finally, I saved the filtered elements into a file named div.npy using np.save().
