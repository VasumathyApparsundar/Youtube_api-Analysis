# YouTube Channel Data Analysis:

This project aims to analyze the data from five popular Tamil YouTube channels. The analysis includes extracting channel statistics, video details, and comments, followed by data preprocessing and transformation. The final data is saved in CSV files for further analysis and visualization.

**Project Overview**

The YouTube Data API is utilized to extract information about the following channels:

1. Village Cooking Channel

2. Nakkalites

3. Micset
   
4. Madan Gowri
   
5. Madras Samayal
   
**The project covers:**

* Extracting channel statistics.
* Retrieving video details for each channel.
* Extracting top-level comments for each video.
* Preprocessing and transforming the data.
* Saving the processed data to CSV files.

**Files**

* youtube_data_analysis.py: Main script to extract and process data.
* youtube_Video_processed.csv: Processed video details.
* channel_stats.csv: Channel statistics.
  
**Requirements**

* Python 3.x
* google-api-python-client
* pandas
* isodate
* IPython


## Key Components

**1. API Interaction:**

* Initialization of the YouTube Data API client.
* Sending API requests to retrieve channel statistics, video details, and comments.

**2. Data Extraction:**

* Retrieving channel statistics using channel_ids.
* Extracting video IDs from the playlists of each channel.
* Extracting detailed information for each video.
* Extracting top-level comments for each video.

**3. Data Transformation and Preprocessing:**

* Converting publication date to datetime format.
* Extracting date, time, and day from the publication date.
* Parsing video duration into minutes and seconds.
* Counting the number of tags for each video.
* Extracting the length of video titles.
* Converting numeric columns to the appropriate data types.

**4. Data Storage:**

* Saving the processed data to CSV files for further analysis.

**5. Future Work**

* Perform detailed data analysis and visualization using tools like Power BI or Tableau.
* Implement sentiment analysis on the extracted comments.
* Explore more advanced features of the YouTube Data API for richer data extraction.
