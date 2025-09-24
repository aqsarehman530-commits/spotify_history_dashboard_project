# Spotify Listening History Analysis

##  Project Overview
This project contains my Spotify listening history, spanning 142,978 records.  
It captures detailed insights about my music consumption habits, including track metadata, listening duration, platforms, playback reasons, and temporal features (day, month, year).

The dataset is provided in CSV format and is suitable for:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Data visualization (listening patterns, top artists, etc.)
- Machine learning projects (recommendation systems, skip prediction, etc.)

 ## Dataset Overview

File name: spotify_history(AutoRecovered).csv

Rows: ~142,978 (large dataset)

Columns (14 total):

spotify_track_uri → Unique Spotify ID for each track

ts → Timestamp (date of play)

platform → Device/platform (e.g., web player, mobile, desktop)

ms_played → Listening duration (milliseconds)

track_name → Name of the song

artist_name → Artist

album_name → Album

reason_start → Why playback started (click, autoplay, etc.)

reason_end → Why playback ended (click, finished, skipped, etc.)

shuffle → Whether shuffle was on/off

skipped → Whether the track was skipped

Day_name → Day of the week

Month_name → Month

Year_name → Year

--

##  Dataset Details
**File:**  -<a href="https://github.com/aqsarehman530-commits/spotify_history_dashboard_project/blob/main/spotify_data.csv">spotify_dataset</a>
**Rows:** 142,978  
**Columns:**
- `spotify_track_uri` → Unique identifier of each track  
- `ts` → Date of playback  
- `platform` → Device/platform used  
- `ms_played` → Duration listened (in milliseconds)  
- `track_name`, `artist_name`, `album_name` → Track metadata  
- `reason_start`, `reason_end` → Why playback started/ended  
- `shuffle`, `skipped` → Boolean indicators  
- `Day_name`, `Month_name`, `Year_name` → Extracted time features  



##  Possible Analysis
- **Top artists and songs** over time  
- **Listening duration trends** across days/months/years  
- **Skip rate analysis** (which songs or artists I skipped most)  
- **Platform usage** (web, mobile, desktop trends)  
- **Shuffle listening patterns**  
- **Start/End reasons** (e.g., autoplay vs. manual selection)  
##  Project file
**File:**  -<a href="https://github.com/aqsarehman530-commits/spotify_history_dashboard_project/blob/main/spotify_project.csv"> spotify_dataset</a>
---


