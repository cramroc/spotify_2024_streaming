# Spotify 2024 Streaming Analysis

Data analysis project exploring the top 500 most-streamed songs globally on Spotify in 2024.

## Overview

This project analyzes streaming trends across artists, genres, release dates, and more. The goal is to uncover patterns and insights from the latest global music listening behavior using Spotify data.

## Project Structure

- `Spotify_2024_Global_Streaming_Data.csv` - Dataset of the top 500 global streams
- `Spotify_Streaming_2024.ipynb` - Jupyter notebook with analysis and visualizations
- `README.md` - Project overview

## How to Use

1. Clone the Repository

2. Install Requirements
  This project requires Python 3 with the following libraries:
- pandas
- matplotlib
- seaborn
- jupyter

3. Run the Jupyter Notebook

4. Explore the Data
  The notebook provides interactive visualizations and analyses of Spotify's 2024 top 500 global songs.

## Findings Overview (from conclusion)

The top five artists in this dataset account for around 40% of the total activity, demonstrating a strong skew in global popularity within the top 500 songs. BTS leads across total streams, monthly listeners, and hours streamed, as well as having the album with the most total streams. Notably, artists like Dua Lipa and Doja Cat appear in the top five for total streams and hours streamed, but not monthly listeners, indicating highly engaged fanbases that listen repeatedly. In contrast, Ed Sheeran and Karol G appear in the top five for monthly listeners but not in the other metrics, suggesting broader but more casual audiences.

No linear correlation was found between skip rate and monthly listeners overall, but BLACKPINK stands out for having the lowest skip rate (16%), suggesting unusually high listener retention. Moreover, weak correlation was found between stream duration and skip rate in genres, with the least skipped genres being Indie and K-pop

Genre-based analysis, restricted to streams from the last 30 days, revealed that Classical music had the highest average streams per song, followed by Rock and Indie. The data also showed that multiple genres performed disproportionately well in certain countries, reflecting strong regional differences in musical taste.

Regarding platform behavior, while skip rates and stream durations were similar across Free and Premium users, a difference was observed in total streams per album: most albums received higher stream counts on Premium, pointing to a potential strategic advantage for artists in targeting Premium user engagement. Furthermore, the albums with the highest platform bias tended to have more Free users than Premium users, such as 1989 (Taylor's Version), suggesting reduced functionalities for Free users reduces their streaming diversity.


## Data Source

The dataset was sourced from [Kaggle - Spotify Global Streaming Data 2024](https://www.kaggle.com/datasets/atharvasoundankar/spotify-global-streaming-data-2024/data).

