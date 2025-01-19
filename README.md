# FIFA 2021 Player Data Analysis

## Project Overview

This project involves the analysis and cleaning of a dataset containing details about FIFA 2021 players. The data was collected and processed to uncover key insights into player attributes such as height, weight, market value, wage, nationality, and more. The analysis includes data cleaning, visualization, and statistical exploration, with the goal of better understanding player performance, market value, and trends in FIFA 2021.

## Tools and Libraries Used

- **Python**
  - **Pandas**: For data manipulation and analysis
  - **Matplotlib**: For data visualization
  - **NumPy**: For numerical calculations
- **Jupyter Notebook**: The environment used to conduct the analysis

## Data Cleaning

The dataset was first cleaned to handle missing values, convert currency values, standardize height and weight measurements, and extract meaningful information from combined columns. The following cleaning steps were taken:

1. **Handling Missing Values**: Missing data was identified and dealt with either by filling, interpolating, or removing data points.
2. **Currency Conversion**: Player values and wages (in EUR) were cleaned by converting currency strings and removing unwanted characters like '€', 'M', and 'K'.
3. **Height and Weight Adjustments**: Heights were converted to centimeters and weight to kilograms.
4. **Feature Extraction**: Relevant features such as team, contract dates, and player positions were extracted and processed.

## Analysis

Key analysis and insights derived from the data include:

- **Top 10 Most Valuable Players**: We identified the players with the highest market values, which ranged from 71 million EUR to 105.5 million EUR.
- **Top 10 Countries with the Most Players**: A bar chart was created to show the countries with the highest representation in FIFA 2021.
- **Player Height and Weight Distribution**: Visualizations were created to explore the relationship between player height and weight.
- **Age vs Market Value**: A scatter plot was generated to study the correlation between player age and market value.
- **Height Categories**: Players were categorized into height ranges (less than 180 cm, 180-190 cm, and greater than 190 cm) to identify trends in player distribution.

## Key Insights

1. **Top 10 Valuable Players**: Kylian Mbappé stood out as the most valuable player in the dataset, followed by players like Lionel Messi and Cristiano Ronaldo.
2. **Player Distribution by Nationality**: The majority of FIFA 2021 players come from countries like England, Germany, and Spain, with smaller representation from countries like Sweden and Japan.
3. **Height and Weight Correlation**: There is a positive correlation between height and weight, with the majority of players falling within the 180-190 cm range. A small number of players exceeded 190 cm, while some fell under 180 cm.
4. **Age and Market Value**: Older players tend to have lower market values, with the exception of high-performing veterans like Messi and Ronaldo.
5. **Height Categories**: The majority of players are between 180 cm and 190 cm, while very few players are taller than 190 cm.

## Visualizations

- **Bar Charts**: To visualize the distribution of players by nationality and the top 10 most valuable players.
- **Scatter Plots**: To explore relationships between player age and market value, and player height and weight.
- **Pie Charts**: To categorize player height ranges and see the distribution.

## Future Improvements

- **Incorporate more features**: Adding player performance stats like goals, assists, and defensive contributions would provide deeper insights.
- **Time Series Analysis**: Track how player values and wages have evolved over the years.
- **Interactive Dashboard**: Create an interactive dashboard using tools like Plotly or Dash to make the analysis more engaging.

## Conclusion

This project provides a comprehensive look into FIFA 2021 player data, uncovering trends in player market value, nationality, and physical attributes. The insights derived from this analysis can be useful for sports analysts, scouts, and enthusiasts to better understand player profiles and trends in football.
