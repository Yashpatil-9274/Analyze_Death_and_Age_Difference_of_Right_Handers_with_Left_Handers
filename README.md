# Analyze_Death_and_Age_Difference_of_Right_Handers_with_Left_Handers

This project involves analyzing data related to handedness and death distribution to explore potential correlations and insights. The project includes several tasks that involve data manipulation, visualization, and probability calculations.

Here is an overview of the tasks involved:

a.	Task 1: Loading Handedness Data and Creating Scatter Plot
-	Importing the required libraries (pandas and matplotlib.pyplot)
-	Loading the handedness data from a CSV file into a pandas DataFrame
-	Creating a scatter plot to visualize the relationship between age and handedness (male and female)

b.	Task 2: Adding Columns for Birth Year and Mean Left-Handedness
-	Creating a new column called "Birth_year" based on the age data
-	Calculating the mean left-handedness and creating a new column called "Mean_lh"
-	Plotting the mean left-handedness against the birth year

c.	Task 3: Calculating P(LH | A) for Specific Ages of Death
-	Importing the numpy package
-	Calculating average left-handedness rates for the early 1900s and late 1900s
-	Filling in the appropriate left-handedness rates for specific ages of death
-	
d.	Task 4: Loading Death Distribution Data and Plotting
-	Loading the death distribution data into a DataFrame from a provided URL
-	Handling the data format and dropping NaN values
-	Plotting the number of people who died as a function of their age

e.	Task 5: Calculating the Overall Probability of Left-Handedness
-	Creating a function (P_lh()) to calculate the overall probability of left-handedness in the population for a given study year
-	Multiplying the number of dead people by the probability of being left-handed for each age group
-	Summing the results and dividing by the total number of dead people to obtain the overall probability

f.	Task 6: Calculating P_A_given_lh()
-	Creating a function (P_A_given_lh()) to calculate the conditional probability of dying at a specific age given left-handedness
-	Utilizing death distribution data and P(LH) to calculate P(LH | A)

g.	Task 7: Calculating P_A_given_rh()
-	Creating a function (P_A_given_rh()) to calculate the conditional probability of dying at a specific age given right-handedness
-	Utilizing death distribution data and P(RH) to calculate P(RH | A)

h.	Task 8: Plotting Probability of Age at Death given Handedness
-	Calculating P_A_given_lh and P_A_given_rh for a range of ages
-	Plotting the results against age to visualize the probability of being a certain age at death given left- or right-handedness

i.	Task 9: Finding the Mean Age at Death for Left-Handers and Right      Handers
-	Multiplying the ages by the left-handed probabilities and calculating the sum to obtain the average age for left-handers
-	Doing the same for right-handed probabilities to obtain the average age for right-handers
-	Printing the mean ages and calculating the difference between them

j.	Task 10: Recalculating Probabilities for a Specific Study Year
-	Updating the study year parameter to 2018 in the calculations of P_A_given_lh and P_A_given_rh
-	Performing the calculations based on the age of death, death distribution data, and the specified study year

These tasks involve data manipulation, probability calculations, and visualization using libraries such as pandas, numpy, and matplotlib.pyplot. The project aims to analyze the relationship between handedness, age at death, and population statistics to uncover insights and patterns within the data.
