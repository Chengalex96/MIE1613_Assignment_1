# MIE1613_Assignment_1
 
Question 1: Find the expected value of theta = E[(X - 4)^+], where a^+ = Max(a, 0)

- Assume that X is uniformly distributed in [2, 8]

- The expected value with a 95% Confidence interval is 1.3328728457484547 +/- 0.036893839228342606

![image](https://github.com/user-attachments/assets/a3702124-5227-44c2-94d8-11d886850d94)

The average goes towards the true expected value as the number of samples increases

Question 2: Simulate the Mean Time to Failure using Monte Carlo Simulation

Assumptions: Two functioning components at time = 0

There are three states: Both working, 1 working, and both failing, we always calculate the transition state (ie. 0 to 1, 1 to 2, 2 to 1, 1 to 0)

Failure time follows a random distribution of 6*np.random(), repair follows a constant 2.5 days.

Calculate the area under the line to determine the average number of working components. 

Plotting the States:

![image](https://github.com/user-attachments/assets/d234d269-54ef-4b70-b1e0-a2a9016ba674)


Question 2b: Calculating the Availability - At least 1 sample functional

Availability is: 90.35%

Question 3: Modelling the problem but with N functioning samples

- the idea is to see that between 1 to N-1 functioning samples, the model behaves the same as it waits for the next repair.

Question 5: Central Limit Theorem

As n increases, the mean converges to 0.50 and the variability shrinks (we see that the horizontal scale is shrinking). The central limit theorem states that if you have a population with mean μ and standard deviation σ and take sufficiently large random samples from the population, then the distribution of the sample means will be approximately normally distributed. We can see that the data fits more into a bell-shaped curve with narrower bands.
