# Spotify_dashboard
Spotify Music Analytics Dashboard | Power BI



## Project Overview
This project presents an **interactive Power BI dashboard** that analyzes Spotify’s music data to uncover insights about song popularity, artist performance, and album trends.  
The dashboard replicates Spotify’s signature dark aesthetic, combining **data storytelling** with clean and engaging visuals.



## Objectives
- Analyze **top-performing artists and songs** based on hits and popularity.  
- Compare **album types, release years, and explicit vs. non-explicit content**.  
- Track **monthly and yearly trends** in song popularity and duration.  
- Showcase **data modeling and DAX calculation skills** for data-driven insights.



## Key Features
Dashboard Pages:-
1. Overview Page
- KPIs: Total Songs, Count of Artists, Average Popularity, Average Duration.  
- Donut Charts: Songs by Album Type, Explicit vs Non-Explicit, Songs by Year.  
- Line Chart: Average Popularity by Month.  
- Bar Charts: Top Artists & Songs by Popularity.  
- Spotify-inspired music player visuals for UI enhancement.

2. Artists Page
- Top Artists by Songs, Popularity, and Hits.  
- Artist-level analysis table with Release Date, Avg. Popularity, and Duration.  
- Filters for interactive artist insights.

3. Songs Page
- Total Songs per Album Type & Average Positions by Artist.  
- Album-level insights: Track Count, Popularity, and Song Metrics.  
- Dynamic cross-filtering between visuals.


## Data Modeling & DAX
- **Power Query Editor** used for cleaning and transforming raw data (removed duplicates, handled nulls, formatted release dates).  
- **Data Relationships** built between Songs, Artists, and Albums tables.  
- Created **custom DAX measures**:
  - Total Songs = COUNT(Songs[Song])
  - Avg Popularity = AVERAGE(Songs[Popularity])
  - Total Artists = DISTINCTCOUNT(Artists[Name])
  - Avg Duration = AVERAGE(Songs[Duration])
  - Songs by Month = COUNTROWS(FILTER(Songs, MONTH(Songs[Release Date]) = SelectedMonth))



## Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Power BI** | Data visualization, modeling, dashboard creation |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Custom calculations and measures |
| **Microsoft Excel / CSV** | Data source |
| **Spotify Dataset** | Song, artist, and album metadata |



## Skills Demonstrated
✅ Data Cleaning & Preparation  
✅ Power BI Dashboard Design  
✅ DAX Formulas & Data Modeling  
✅ Trend & KPI Analysis  
✅ Interactive Visuals & UX Design  



## Outcome
Delivered a **fully interactive, Spotify-themed Power BI dashboard** that visualizes music data trends and artist analytics in a single glance.  
The project highlights **data storytelling, analytical thinking**, and **dashboard aesthetics** — perfect for business intelligence portfolios.



## 📷 Dashboard Preview
Index Page  
![Index Page](https://github.com/Nidhi-0110/Spotify_dashboard/blob/main/index.png)

Overview Page  
![Overview Page](https://github.com/Nidhi-0110/Spotify_dashboard/blob/main/Overview.png)

Artists Page  
![Artists Page](https://github.com/Nidhi-0110/Spotify_dashboard/blob/main/Artist.png)

Songs Page  
![Songs Page](https://github.com/Nidhi-0110/Spotify_dashboard/blob/main/Songs.png)

