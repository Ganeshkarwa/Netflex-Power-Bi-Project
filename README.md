
# Netflix Power BI Analysis

Welcome to the Netflix Power BI Analysis project! This project aims to provide insightful 
visualizations and analyses of Netflix ratings, votes, movies, and TV shows using Power BI.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Data Sources](#data-sources)
- [Visualizations](#visualizations)
- [Contributing](#contributing)
- [Contact](#contact)

## Overview

This project leverages Power BI to analyze and visualize data related to Netflix. 
The primary objectives are to understand the distribution of ratings and votes, explore the content library of movies and TV shows, 
and derive meaningful insights that could help users make informed decisions.

## Features

- **Rating Distribution:** Visualizes the distribution of ratings across different movies and TV shows.
- **Votes Analysis:** Analyzes the number of votes received by various titles.
- **Content Analysis:** Provides insights into the Netflix content library, including genre breakdown, release year trends, and more.
- **Interactive Dashboards:** Interactive Power BI dashboards that allow users to explore the data dynamically.

## Data Sources

### About Dataset

**Context:**
The dataset contains the list and metadata of all TV Shows and Movies available on Netflix, currently about 7,000 entries, sourced from the IMDb website.

**Content:**
The dataset file is `netflix_list.csv`, and it includes the following fields:
- **imdb_id:** Unique show identifier.
- **title:** Title of the show.
- **popular_rank:** Ranking as given by IMDb when filtered by popularity.
- **certificate:** Contains the age certifications received by the show. Many null values.
- **startYear:** Year when the show was first broadcasted.
- **endYear:** Year when the show ended.
- **episodes:** Number of episodes in the show (1 for movies).
- **type:** Movie or Series.
- **orign_country:** Country of origin of the show.
- **language:** Language of the show.
- **plot:** Synopsis of the show.
- **summary:** Summary of the story of the show.
- **rating:** Average rating given to the show.
- **numVotes:** Number of votes received by the show.
- **genres:** Genre the show belongs to.
- **isAdult:** 1 if adult content present, 0 if not.
- **cast:** Main cast of the show in list format.
- **image_url:** Link to poster image.

**Acknowledgements:**
This data was collected from the IMDb website through web scraping.
The data was collected by scraping the shows' ranking pages filtered to show Netflix-related content (16,000+ entries) and noting down the `imdb_id`, 
followed by a single page search for each collected ID and unique title name.


## Visualizations

The project includes the following key visualizations:

- **Ratings Distribution Histogram:** Shows the distribution of ratings across all titles.
- **Votes Scatter Plot:** Displays the relationship between ratings and the number of votes.
- **Genre Breakdown Pie Chart:** Visualizes the distribution of content genres.
- **Release Year Trend Line:** Shows the trend of content releases over the years.
- **Top Rated Titles Bar Chart:** Highlights the top-rated movies and TV shows.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please feel free to open an issue or submit a pull request.

## Contact

If you have any questions or feedback, feel free to contact me at gkarwa03@gmail.com.

Happy analyzing!

![image](https://github.com/Ganeshkarwa/Netflex-Power-Bi-Project/assets/140792447/07d2a2d1-0544-41b7-ac5d-2c7e3bd9d202)

![image](https://github.com/Ganeshkarwa/Netflex-Power-Bi-Project/assets/140792447/1f15bc40-cbe3-49ba-a153-686a6d12e9d6)
