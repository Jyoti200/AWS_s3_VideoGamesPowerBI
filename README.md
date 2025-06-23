Video-Games-Dashboard
##Problem Statement
This dashboard provides actionable insights into the global video game industry, enabling stakeholders to explore trends in game sales across various genres, platforms, and regions. It helps identify the most successful publishers, popular game categories, and market preferences across time.
By analyzing key metrics such as global and regional sales, genre performance, platform trends, and top publishers, the dashboard supports data-driven decisions for developers, publishers, and marketers in the gaming industry.

##Steps Followed
Step 1: Connected Power BI to AWS S3 using Amazon Athena via the ODBC connector. Multiple CSV files stored on S3 were queried through Athena using SQL.

Step 2: Appended multiple datasets (e.g., different regional sales files or multiple time periods) into a single unified table using Power Query.

Step 3: Performed data cleaning and transformation in Power Query:
1. Standardized column names and data types.
2. Removed rows with missing values in critical fields (Year, Publisher, Global_Sales).
3. Removed duplicates and trimmed text fields.

##Step 4: Enabled column profiling for the entire dataset and verified data quality using:

Column Distribution
Column Profile
Column Quality

##Step 5: Built interactive visualizations:

Bar charts: Top 10 games, top publishers.
Line charts: Game release trends over the years.
Waterfall Charts: Regional sales comparison (North America, Europe, Japan) by Genres.
Card visuals: Total sales, number of games, top publisher, etc.
Slicers: Platform, Publisher, Year, Genre, Region.

##Step 7: Customized themes, added titles, and inserted explanatory text boxes for better user understanding.

Power BI Desktop
Link: 

##Insights
[1] Top Games
Top Global Seller: Wii Sports with 80M+ units.
Best Sellers in NA & EU: GTA V, Call of Duty titles.
Top Game in Japan: Pokémon Red/Blue/Green
[2] Platform Trends
Most Lucrative Platforms:
PS2 (Highest number of top sellers)
Xbox 360, Wii

[3] Genre Analysis
Global Favorites: Action, Shooter, Sports
Japan: Dominated by Role-Playing Games (RPGs)
Europe/NA: Strong preference for Shooter and Sports

[4] Publisher Performance
Top Publishers by Global Sales:
Nintendo
Electronics Arts
Activision

[5] Time Trends
Peak Release Years: 2006–2010
Sales Trend: Gradual decline post-2012 (as per available data)

##Summary
This Power BI dashboard, powered by Athena and AWS S3, integrates and analyzes data from multiple sources, offering a 360-degree view of the video game industry. It helps answer:

What games and genres dominate each region?
Which publishers consistently deliver bestsellers?
Which platforms have the highest sales potential?
How do game sales evolve across time?
Whether you’re a publisher, investor, analyst, or gamer—this dashboard provides meaningful insights to navigate the dynamic world of video games.
