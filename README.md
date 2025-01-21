# Analyzing-TV-Data
Analyzing TV Data 

Project Description:
This project explores the Super Bowl, one of the most watched events globally, by analyzing its associated game, TV, and halftime show data from the first Super Bowl in 1967 to Super Bowl LII in 2018. The goal is to uncover insights about game outcomes, viewership trends, advertising costs, and halftime performances. These insights are drawn through data wrangling, statistical analysis, and visualization techniques.

Steps Taken:
1. Data Loading and Initial Inspection:
Datasets Used:
Game Data: Includes Super Bowl scores and game stats.
TV Data: Tracks viewership, ratings, and advertising costs.
Halftime Musicians: Covers halftime show performers and song counts.
Loaded the data into pandas DataFrames and inspected the first few rows to understand the data structure.
Used .info() to identify missing values, data types, and potential inconsistencies.
2. Data Cleaning and Preparation:
Identified and noted missing values in key columns:
TV data had null values for total_us_viewers, rating_18_49, and share_18_49.
Halftime musician data had missing entries for the number of songs performed (num_songs).
Filtered and refined the data for meaningful analysis:
Excluded Super Bowl I from TV data due to its split broadcast.
Filtered non-marching bands for halftime performance analysis.
3. Data Exploration:
Game Outcomes:

Visualized the distribution of combined game points using histograms.
Identified high-scoring games (e.g., Super Bowl LII with 74 points) and low-scoring ones (e.g., Super Bowl IX with 16 points).
Examined point differences to highlight the closest games (e.g., a 1-point difference in 1991) and the biggest blowouts (e.g., a 45-point difference in 1990).
Viewer Behavior:

Merged game and TV data to assess the relationship between blowout games and viewership.
Created scatter plots with regression lines to reveal a slight negative correlation between point differences and household share.
Ad Costs and Viewership Trends:

Plotted line graphs to track the evolution of ad costs, viewership, and household ratings over time.
Highlighted the lag between viewership growth and ad cost increases, showing delayed network reactions.
Halftime Show Analysis:

Counted appearances of halftime performers, revealing the most prolific acts (e.g., Grambling State University Tiger Marching Band with 6 shows).
Analyzed the number of songs performed per show, noting Justin Timberlake’s record-breaking 11 songs in 2018.
4. Insights and Conclusions:
Game Dynamics:
Most games are competitive with point differences clustering around a median range. Blowouts negatively impact viewership.
TV and Ads:
Advertising costs have soared, driven by the growing prestige and viewership of the Super Bowl.
Halftime Shows:
Modern halftime shows became cultural spectacles post-Michael Jackson’s 1993 performance, shifting from traditional acts to global superstars.
Skills Applied:
Technical Skills:
Data Wrangling:
Loaded, inspected, and cleaned datasets using pandas.
Handled missing values and filtered irrelevant entries for focused analysis.
Visualization:
Used Matplotlib and Seaborn for:
Histograms (e.g., point differences, song counts).
Line plots (e.g., trends in viewers and ad costs).
Scatter plots with regression (e.g., point differences vs. viewership).
Statistical Analysis:
Explored distributions, calculated averages, and identified correlations.
Data Merging:
Combined game and TV data to investigate relationships across datasets.
Analytical Skills:
Trend Analysis:
Tracked long-term patterns in viewership and advertising costs.
Event Impact:
Analyzed how game outcomes (e.g., blowouts) influenced viewer behavior.
Categorical Insights:
Identified prolific halftime performers and their contributions to Super Bowl culture.
Storytelling:
Highlighted key moments in Super Bowl history (e.g., record-breaking games and halftime performances).
Connected data insights to real-world implications, like network revenue strategies and cultural shifts.
This project demonstrates a robust combination of data analysis and storytelling, making the Super Bowl’s dynamics accessible and engaging through data-driven insights. 
