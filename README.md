 # Video Game Data Analysis & Visualization
 ##Project Overview
This project focuses on the end-to-end process of data science: collecting, cleaning, analyzing, and visualizing data from the video game industry. Using the RAWG API, the analysis explores trends in game releases, popular genres, and platform distributions to extract meaningful market insights.

 ##Tools & Technologies
Language: Python 

Libraries: - Pandas (Data Manipulation)

Matplotlib (Data Visualization)

Requests (API Data Fetching)

Ast (Literal Evaluation)

## Key Objectives
Fetch real-time data using the RAWG API (over 2,000 game records).

Perform extensive Data Cleaning (handling null values, duplicates, and data type conversions).

Conduct Exploratory Data Analysis (EDA) to identify top-rated games and peak release periods.

Create Visualizations to represent platform popularity and genre distribution.

 ## Quick Insights
Based on the analysis performed in this notebook:

Top-Rated Game: The Witcher 3: Wild Hunt - Complete Edition leads in player ratings.

Peak Release Year: 2016 saw the highest number of game releases.

Busiest Month: October is the most popular month for game launches.

Dominant Genres: Action and Shooter games represent the largest market share.

Leading Platform: PC remains the most host-accessible platform for the dataset.

 ## Dataset Structure
The final cleaned dataset includes the following features:

name: Title of the game.

released: Release date.

rating: Player rating (0-5).

platforms: Available gaming platforms.

genres: Category/Genre of the game.

 ## How to Use
Clone this repository or download the .ipynb file.

Ensure you have the required libraries installed: pip install pandas matplotlib requests.

You will need a RAWG API Key to fetch new data (the current notebook uses a pre-set key for demonstration).
