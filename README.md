# Spotify Music Analysis Dashboard

## Overview
A single page interactive Power BI dashboard analysing 952 tracks and 489 billion
streams across multiple artists and release periods. Built to uncover streaming
patterns, track performance drivers, and music attribute trends using real world
Spotify data spanning multiple years and platforms.

---

## Objectives
- Analyse total stream volumes and track performance across artists, days, and
  months in a single unified view
- Identify which tracks and artists are driving the highest streaming numbers
  across Spotify, Deezer, and Apple Music playlists
- Understand how music attributes such as danceability, energy, and valence
  profile the sonic characteristics of top performing tracks
- Surface day of week and monthly streaming patterns to understand when audiences
  engage most with music content

---

## Dashboard Pages

| Page | Description |
|---|---|
| Overview | KPI cards for total streams and total tracks, daily average streams visual, main tracks table with album art, monthly average streams area chart, most played track card with music metadata, and music attribute indicators |

---

## Screenshots
> All screenshots are stored in the `images` folder

### Overview Page
![Overview Page](images/overview_page.png)
*Full dashboard view showing KPI cards, tracks table, daily and monthly stream trends and music attribute breakdown*

---

## What I Built
- Designed an end to end Spotify analytics dashboard using a real world dataset
  of 952 tracks, demonstrating ability to work with entertainment and consumer
  behavioural data at scale
- Built a dynamic tracks table with embedded album art using cover URL integration,
  displaying streams and playlist inclusions across Spotify, Deezer, and Apple
  Music side by side for cross platform comparison
- Engineered DAX measures for Total Streams using SUM and Total Tracks using
  DISTINCTCOUNT to ensure accurate and non duplicated track counting
- Implemented a Most Played Track card displaying released date, artist name,
  key, BPM, and mode, giving users instant context on the top performing track
  without any additional filtering
- Created a music attributes panel displaying Danceability, Energy, Liveness,
  Speechiness, Valence, and Acousticness percentages to profile the sonic
  characteristics of the filtered track selection
- Built a monthly average streams area chart using AVG aggregation across month
  name to surface seasonal streaming trends across the catalogue
- Applied a custom Spotify branded theme using the official green palette with
  a bespoke background image, delivering a publication ready dashboard that
  mirrors real world product design standards
- Configured 4 slicers (Date range, Artist Name, Track Name, and Spotify Tracks)
  enabling granular filtering across every visual simultaneously

---

## Key Insights
- Total streams reached 489 billion across 952 tracks, with La Bachata by Manuel
  Turizo emerging as one of the highest streamed individual tracks at over
  1.2 billion streams
- Tuesday recorded the highest daily average streams at 772.71M while Friday
  recorded the lowest at 447.73M, suggesting mid week is peak consumption time
  for music audiences
- Monthly average streams peaked in July at 734.64M before declining steadily
  through to December, indicating a strong mid year streaming surge across
  the dataset
- Average Energy across the dataset is significantly higher than Danceability,
  suggesting the catalogue skews toward high energy tracks over danceable ones
- Blinding Lights by The Weeknd ranked as the most played track overall with a
  release date of November 2019, confirming that catalogue tracks continue to
  dominate streaming volumes over newer releases

---

## Recommendations
- Fix aggregation of BPM and music attribute fields from SUM to AVERAGE to ensure
  metrics are statistically meaningful when multiple tracks are selected
- Replace the current day of week treemap with a horizontal bar chart sorted by
  average streams to make the daily pattern immediately readable
- Add a dedicated Date Table to the data model to enable proper time intelligence
  functions and accurate month over month trend calculations
- Introduce a Year over Year comparison measure to determine whether streaming
  volumes are growing or declining across the catalogue over time
- Add a correlation visual between music attributes such as danceability and
  energy against stream counts to quantify which sonic characteristics drive
  higher performance
- Expand the dataset beyond July 2023 to keep the analysis current and relevant
  for ongoing portfolio use

---

## Tech Stack
- Power BI Desktop
- DAX
- Power Query (M)
- Data Modelling
- Custom Themes
- Conditional Formatting
- URL Based Image Integration
- Cross Platform Playlist Analysis (Spotify, Deezer, Apple Music)

---

## Folder Structure

```
Spotify-Music-Analysis/
│
├── Images/
│   └── overview_page.png
│
├── Sportify_Analysis_Dashboard.pbix
└── README.md
```

---

## Contact
**Harish Thota**  
Data Engineer and Business Analyst  
harishthota001@gmail.com

[Portfolio](https://harish-thota1.github.io/Analyst-Portfolio/) · [LinkedIn](https://www.linkedin.com/in/harish-thota/)
