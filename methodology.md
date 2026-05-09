## Data source
- My data source is from CORGIS website : [billionaires_data](https://corgis-edu.github.io/corgis/csv/billionaires/) 

## Data preparation/Cleaning
- I wanted to analyze the genders and some people did not have their gender disclosed so I had to modify my data for only male and female 
- 
- My data columns had `.` on them, so I had to modify them in my code so I would be able to use it more efficiently.
- The way I wanted to use my data did not involved many numbers to it, more strings. I had to do some research on how to modify or use different aspects os Pandas and Matplot so I would be able to do what I wanted. 
 1. Learned how to use Unstack to turn gender into columns
 2. Learned .apply is used to do something to every value in the column
 3. Used str(x) to make sure every value was a string and .lower to convert them to lower case
 4. Using Matplotlib styling features learning how to change colors in the graphs to make them more appealing 
 5. Learned that alpha is the transparency of the dots in a scatterplot
 6. Barh is an horizontal bar graph
 7. Learned that Figsize controls the size of the figures
 8. I frequently used .value_counts to quickly identify the most common industries, countries, and wealth categories in the dataset


## Assumptions
- Divided the people into two gender only (some people were not male or female )
- Used only top 10 countries to simplify my data 
- Removed married couples in one of the representations to keep only two (female or male)
- I also assumed that billionaire citizenship could reasonably represent the geographic location of wealth concentration.
- I assumed that the information provided in the dataset was accurate and consistently categorized across years

## Limitations
- I wanted to do a map graph with a world map but it was not supported by the library 
- The dataset only represents billionaires included in the CORGIS dataset, so it may not fully reflect all billionaires worldwide.
- Focusing only on the top 10 countries may exclude important patterns from smaller countries.
- Might have not representad other gender when doing it 
- Another limitation was that much of my analysis relied on categorical data such as gender, country, and industry rather than deeper numerical or financial analysis.
- Some columns also contained missing or inconsistent values, which limited how much detail could be included in certain visualizations.
