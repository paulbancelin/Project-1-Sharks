# Project-1-Sharks
# 1. Import the libraries to have access to functions.
"""
import pandas as pd
import matplotlib.pyplot as plt
import matplotlib.cm as cm

"""
# 2. Import the DataFrame file.
"""
df= pd.read_csv("data/attacks.csv", encoding = "latin1")

"""
# 3. Print the columns in to a list.
# 4. Drop the columns that I don’t need according to the questions and create a new DataFrame.
# 5. Delete null values from the new DataFrame.
# 6. Extract only the surfing values from the column Activity.
# 7. Show the first row and the last row to check in what year the attacks start.
# 8. Drop the last row as the year of it was 0.0.
# 9. Reset the index to have the data more organized.
# 10. Graphic to show the exponential increase on 60’s decade.
# 11. Print values_counts of Fatal column to know how many of the attacks were fatal and answer the first question.
# 12. Create a list of the years of Year columns.
# 13. Perform an If statement to verify if the year 1966 is on the list.
# 14. Print the index of 1965 and 1967 as 1966 isn’t on the list.
# 15. Print how may rows are above and under 1966 using 1965 and 1967 as a start indexes to answer the second question.
# 16. Create two different DF, one 10 years before and one 10 years after 1966 and use function .shape in each one to know witch one has more and answer question 3.
# 17. Print value_counts of column Country, to answer question 4.
# 18. Extract only the USA values from the DF, create a new DF and print value_counts of column Area to answer question 5. 