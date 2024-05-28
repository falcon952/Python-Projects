# Video Games Sales Data Analysis

# Overview
This repository contains an analysis of the video game sales dataset, vgsales.csv. The dataset provides detailed information on video game sales across different regions, platforms, genres, and publishers from 1980 to 2020. The analysis aims to extract insights regarding sales distribution, trends over the years, and the popularity of genres and platforms.

# Dataset Information
The dataset consists of 16,598 entries and 11 columns:

Rank: Global rank of the game based on sales.

Name: Name of the game.

Platform: Platform of the game release (e.g., PS4, Xbox, etc.).

Year: Year of the game's release.

Genre: Genre of the game (e.g., Action, Sports, etc.).

Publisher: Publisher of the game.

NA_Sales: Sales in North America (in millions).

EU_Sales: Sales in Europe (in millions).

JP_Sales: Sales in Japan (in millions).

Other_Sales: Sales in other regions (in millions).

Global_Sales: Total global sales (in millions).



# Data Cleaning
## Missing Values:

The Year column had 271 missing values, which were imputed with the median year.

The Publisher column had 58 missing values, which were filled with 'Unknown'.

# Sales Analysis

## Sales Statistics:

Average North America Sales: 0.26 million units
Average Europe Sales: 0.15 million units
Average Japan Sales: 0.08 million units
Average Other Regions Sales: 0.05 million units
Average Global Sales: 0.54 million units

## Total Sales by Region:

![video_games_analysis](/Video_games/img/total_sales_region.png)

North America: 4392.62 million units|
Europe: 2435.62 million units| 
Japan: 1285.74 million units| 
Other Regions: 797.93 million units| 
North America leads in total sales, followed by Europe, Japan, and other regions.

## Total Global Sales by Year:
Total global sales show a rise until around 2008-2009, followed by a decline.

![video_games_analysis](/Video_games/img/Total_sales_global.png)

## Total Europe Sales by Year:

The total Europe sales were calculated for each year, showing trends in sales over time.

![video_games_analysis](/Video_games/img/Total_sales_europe.png)

## Total North America Sales by Year:

Depicts North America sales trends over the years. 

![video_games_analysis](/Video_games/img/Total_sales_NA.png)

## Total Japan Sales by Year:

Similarly, the total Japan sales were calculated for each year, illustrating how the Japanese market has evolved.

![video_games_analysis](/Video_games/img/Total_sales_japan.png)


## Distribution of Games by Year:
The distribution of games by year shows a peak around 2008-2009.

![video_games_analysis](/Video_games/img/Distribution_sales.png)

Top 10 Genres by Number of Games:
The most common genre is 'Action', followed by 'Sports' and 'Misc'.

![video_games_analysis](/Video_games/img/top_10_genres.png)

Top 10 Platforms by Number of Games:
The most common platform is 'DS', followed by 'PS2' and 'PS3'.

![video_games_analysis](/Video_games/img/top_10_platform.png)


Correlation Heatmap:
Correlation heatmap shows strong correlations between regional sales and global sales.

![video_games_analysis](/Video_games/img/correlation.png)


# Conclusion
The analysis of the video game sales dataset reveals significant insights into the video game industry. North America has the highest sales, followed by Europe and Japan. The peak of game releases and sales occurred around 2008-2009. Action games dominate the genre landscape, and the DS platform has the highest number of game releases. These insights can help in understanding market trends, consumer preferences, and the overall dynamics of the video game industry.
