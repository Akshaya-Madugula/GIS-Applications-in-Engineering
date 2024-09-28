# GIS-Applications-in-Engineering
This mini project is basically dealing with the analysis of the bridge data of Texas for the years 2022 and 2023 by using techniques of GIS with the Python programming language.
Here's what I did in this project:
1. I initiated by loading two datasets: 2022_Data.csv and 2023_Data.csv. Each of these datasets has a list of bridges, including latitude and longitude in non-decimal format.
2. Then, I cleaned and processed the information with the help of a library called Pandas. I filtered out any rows that contain null values within the Latitude and Longitude columns.
Coordinate Conversions
3. I created a function, dms_to_dd() that converted the DMS-formatted coordinates in both my datasets to Decimal Degrees. I then used another function, process_coordinates() to effect this conversion and clean up both sets for analysis. Visualization
4. Visualizing the Texas county boundaries: Using GeoPandas done by projecting the data to the WGS84 coordinate system, EPSG:4326.
5. A plot was designed that could map the county boundaries along with the newly surveyed bridge locations for the year 2023.


6. I wanted to determine which bridges surveyed in 2023 were not present in the dataset from 2022. First, I used the MATCH function in Excel to compare the structure numbers from both years. I filtered the 2023 dataset only to find the bridges that did not match any in the 2022 dataset.
(Matching and filtering common bridge records within the two years were tricky for me using Python; thus, I had to start considering Excel as an alternative means. I had a fair idea on what to do, but I wasn't able to excute it, by the time I thought I understood how to do it, I had an hour! Here's a Theoretical Idea on what I should do to proceed:)

7. Add Age Column: Calculate the age of each bridge by subtracting the year built from the current year (2024) and add this as a new column.
8. Create a new dataset containing only the bridges surveyed in 2023 that were not present in the 2022 dataset.
9. Select relevant columns (e.g., ADT, deck area, span length, age) as independent variables and the condition of the deck as the dependent variable.
10. Split the data into training and testing sets.
11. Create a pipeline to handle missing values and fit a logistic regression model.
12. Fit the model on the training data.
13. Evaluate the model’s performance on the test data using confusion matrix and classification report.
14. Plot/Visualize.

(I have discussed it with my classmates Sushant and Pravin, while figuring out this assignment. And ofcourse Dr. Uddameri's lectures and tips during the last class, along with Mr. Aalok's much appreciated help too. I can assure myself that Python is not a monster, and put enough effort to understand, I can work on it.)

