# Netflix Content Strategy Analysis (2023)

## Project Overview
This project aims to analyze Netflix's content strategy based on viewership patterns, content type, language distribution, and release timing using Python. The analysis is performed on Netflix content data from 2023, including information about titles, release dates, languages, content type (show or movie), and viewership hours.

## Dataset
The [dataset](https://statso.io/netflix-content-strategy-case-study/) used in this project contains:
- Title
- Release Date
- Language
- Content Type (Show or Movie)
- Availability Status
- Viewership Hours (2023)

## Objective
The primary objectives of this project are:
- To analyze the distribution of viewership between Shows and Movies.
- To understand which languages dominate Netflix's viewership.
- To identify seasonal and monthly trends in viewership.
- To explore content release patterns and their impact on viewership.
- To highlight the most successful content titles and their characteristics.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- plotly

## Data Cleaning and Preprocessing
The **Hours Viewed** column was cleaned and converted into numeric format to ensure accurate analysis.

## Content Type Viewership Distribution
The analysis shows that Shows dominate the total viewership hours compared to Movies.

 
![Content Type Viewership Distribution](images/content%20type%20viewership.png)

## Language Distribution
English content significantly dominates Netflix’s viewership, followed by Korean content.

  
![Language Distribution](https://github.com/Sourabh1710/Netflix-Content-Strategy-Analysis/blob/main/images/Total%20Viewership%20Hours%20by%20Language.png)

## Viewership by Month
A notable increase in viewership is observed during **June** and **December**, indicating seasonal trends and strategic content releases.

 
![Viewership by Month](https://github.com/Sourabh1710/Netflix-Content-Strategy-Analysis/blob/main/images/Total%20Viewership%20Hours%20by%20Release%20Month.png)

## Top Content by Viewership
| Title                        | Language | Type  | Hours Viewed (Million) |
|------------------------------|----------|-------|----------------------|
| The Night Agent: Season 1    | English  | Show  | 812.1               |
| Ginny & Georgia: Season 2    | English  | Show  | 665.1               |
| King the Land: Limited Series | Korean   | Movie | 630.2               |
| The Glory: Season 1         | Korean   | Show  | 622.8               |
| ONE PIECE: Season 1         | English  | Show  | 541.9               |

## Viewership Trends by Content Type
Shows consistently have higher viewership than Movies, peaking in **December**, while movies experience occasional spikes.

  
![Viewership Trends by Content Type](https://github.com/Sourabh1710/Netflix-Content-Strategy-Analysis/blob/main/images/Viewership%20Trends%20by%20Content%20Type%20and%20Release%20Month.png)

## Viewership by Season
Viewership peaks significantly in the **Fall** season, with over 80 billion hours viewed.

  
![Viewership by Season](https://github.com/Sourabh1710/Netflix-Content-Strategy-Analysis/blob/main/images/Total%20Viewership%20Hours%20by%20Release%20Season.png)

## Content Releases Across Months
Despite a steady number of content releases, viewership increases sharply in **June** and **December**, indicating that audience engagement is influenced by content appeal rather than the number of releases.

  
![Content Releases Across Months](https://github.com/Sourabh1710/Netflix-Content-Strategy-Analysis/blob/main/images/Total%20Viewership%20Hours%20by%20Release%20Month.png)

## Content Releases by Weekday
Most content releases occur on **Fridays**, with the highest viewership recorded on that day.

  
![Content Releases by Weekday](https://github.com/Sourabh1710/Netflix-Content-Strategy-Analysis/blob/main/images/Weekly%20Release%20Patterns%20and%20Viewership%20Hours.png)

## Strategic Release Dates
Netflix strategically releases content around key holidays and events, such as:
- **New Year's Period**: The Glory: Season 1, La Reina del Sur: Season 3
- **Valentine's Day**: Perfect Match: Season 1, The Romantics: Limited Series

## Conclusion
The analysis reveals that Netflix's content strategy is heavily focused on:
- Shows over Movies
- English and Korean content
- Strategic content releases around holidays and weekends
- Maximizing viewership during Fall and December

This project highlights how Netflix aligns its content releases with audience preferences and global trends to optimize engagement.

## Author
Aftab Aziz

