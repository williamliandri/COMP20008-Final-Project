There are some parts of code that were written for this project:

 1. Libraries 
    This part contains all of the libraries that were used on this project.

 2. Function to Correct Alphabetical
    A function named "correct_alphabetical" to correct the alphabetical given the LGA 
    name (such as, converts GREATER GEELONG to Greater Geelong). 
    This code is used when wrangling the crime and the liquor data.

 3. Function to Put the Data into a Dictionary
    A function named "calculate_into_dict" to calculate the number of crimes and
    population in each LGA in Victoria and store the data in a dictionary. This code
    also remove a noisy data with LGA named 'Unincorporated Vic'.

 4. Calculate the Number of Crimes
    This part will read the crime data from the csv file named "Crime_location.csv"
    and record the number of crime in each LGA by using "calculate_into_dict"
    function. This part also sort the crime data and create a data frame.

 5. Movement on the Crime Rates between 2012 and 2015
    Calculate the total number of crimes between 2012 and 2015 and create a line 
    chart to show the increase in the crime rates for the span of 3 years.

 6. Calculate the Number of Population in Each LGA in Victoria
    Read the population data from the csv file named "Population_by_LGA_2015.csv" 
    to calculate the number of population in each LGA in Victoria by using
    "calculate_into_dict" function.

 7. Normalised the Number of Crimes Data
    Normalising the data by dividing the number of crimes with the number of
    population in each LGA in Victoria and store the data in a dictionary. For the
    missing value, it will  be divided with the average number of population in
    Victoria. This part also detect a missing value in the population data with LGA
    named "Queenscliffe".

 8. Calculate the Number of Liquor Stores
    There are 2 function definitions in this part, which were:
	- "calc_liquor_store": a function to calculate the number of liquor stores in
				each LGA and store the data in a dictionary
	- "find_LGA_name" : a function to find the "LGA Name" given the "Council
			    name" (as explained on the project in "Integration"
			    paragraph).
   
    There is also code to read the liquor data from the csv file named
    "Liquor_metro_2015.csv" and "Liquor_region_2015.csv" to calculate the number of
    liquor stores in each LGA and store the data in a dictionary. A data frame 
    was also created to show the number of crimes and the number of liquor stores in
    each LGA in Victoria.

 9. Bar Chart of Top 5 LGAs with the Highest Crime Rates
    Plot a bar chart to show top 5 LGAs with the highest crime rates

10. Bar Chart of Number of Liquor Stores in 5 LGAs with the Highest Crime Rate
    Plot a bar chart to show the number of liquor store in 5 LGAs with the highest
    crime rates

11. Bar Chart of Top 5 LGAs with the Highest Crime Rates and the Number of 
    Liquor Stores in those LGAs
    Plot a bar chart showing the crime rates and the number of liquor stores in 5
    LGAs with the highest crime rates.

12. Distribution of Liquor Stores in Victoria
    Plot a bar graph showing the number of liquor stores in each LGA in Victoria. 
    The data was already sorted in descending order.

13. Number of Crimes per 100,000 People in Each LGA Based on the Type of Crimes
    This part contains a function named "calc_type_crime" to calculate the crime
    rates for 6 type of crimes and store the data in 6 different dictionaries.

14. Bar Chart of the Total Number of Crimes Based on the Type of Crimes
    Print the crime rates for 6 type of crimes and also plot a bar chart showing the 
    the crime rates for each type of crimes

15. Calculate Pearson Correlation
    There are 2 function definitions in this part:
	- "calc_aver": a function to calculate the average value given the data in a 
			dictionary.
	- "pearson_correl": a function to calculate the Pearson correlation given the 
			     2 dictionaries

16. Calculate Normalised Mutual Information
    There are 4 function definitions in this part:
	- "normalised_mutual_information": a function to calculate the Normalised
					     Mutual Information by calling the other 3
					     functions.
	- "find_group_bin": a function to put the data into a given bin class.
	- "calc_entropy" : a function to calculate the entropy.
	- "calculate_mutual_info": a function to calculate the mutual information.

17. Merge the Data into a Single List
    A function named "create_list_crime_liquor" to put the crime rates and the number
    of liquor stores in a single array.

18. Find 3 Bins Equal Length Discretisation
    A function named "bin_equal_length_discretisation" to find the bins using the 
    equal-width bid technique. This bin will be used when calculating the NMI.

19. Data with Outliers
    This part contains:
	- Boxplot with outliers for the crime data.
	- Boxplot with outliers for the liquor data.
	- Scatter plot, Pearson correlation and NMI result between the crime rates
	  and the number of liquor stores.

20. Data without Outliers
    This part contains:
	- A function named "clean_outliers": to remove the outliers from the data and
					       store it in a new dictionary.
	- List of LGA names that considered as outliers.
	- Scatter plot, Pearson correlation and NMI result between the crime rates
	  and the number of liquor stores (exclude the outliers).

21. Crime Against the Person with Outliers
    Plot a scatter plot and calculate both the Pearson correlation and NMI for crime
    with category "Crime Against the Person".

22. Crime Against the Person without Outliers
    Plot a scatter plot and calculate both the Pearson correlation and NMI for crime
    with category "Crime Against the Person" (after cleaning the outliers).

23. Property and Deception Offences with Outliers
    Plot a scatter plot and calculate both the Pearson correlation and NMI for crime
    with category "Property and Deception Offences".

24. Property and Deception Offences without Outliers
    Plot a scatter plot and calculate both the Pearson correlation and NMI for crime
    with category "Property and Deception Offences" (after cleaning the outliers).

25. Drug Offences with Outliers
    Plot a scatter plot and calculate both the Pearson correlation and NMI for crime
    with category "Drug Offences".

26. Drug Offences without Outliers
    Plot a scatter plot and calculate both the Pearson correlation and NMI for crime
    with category "Drug Offences" (after cleaning the outliers).

27. Public Order and Security Offences with Outliers
    Plot a scatter plot and calculate both the Pearson correlation and NMI for crime
    with category "Public Order and Security Offences".

28. Public Order and Security Offences without Outliers
    Plot a scatter plot and calculate both the Pearson correlation and NMI for crime
    with category "Public Order and Security Offences" (after cleaning the outliers).

29. Justice Procedures Offences with Outliers
    Plot a scatter plot and calculate both the Pearson correlation and NMI for crime
    with category "Public Order and Security Offences".

30. Justice Procedures Offences without Outliers
    Plot a scatter plot and calculate both the Pearson correlation and NMI for crime
    with category "Public Order and Security Offences" (after cleaning the outliers).
    
29. Other Offences with Outliers
    Plot a scatter plot and calculate both the Pearson correlation and NMI for crime
    with category "Other Offences".

30. Other Offences without Outliers
    Plot a scatter plot and calculate both the Pearson correlation and NMI for crime
    with category "Other Offences" (after cleaning the outliers).

31. Scatter Plot for Each Type of Crimes with Outliers
    Plot 6 type of crimes in a single scatter plot.
 
32. Scatter Plot for Each Type of Crimes without Outliers
    Plot 6 type of crimes in a single scatter plot after removing the outliers

					---THE END---
