# 🎵 Spotify Analysis Dashboard

A comprehensive, multi-page analytics dashboard for visualizing Spotify music data — covering song metrics, artist performance, popularity trends, and album insights.
---

## 📑 Pages Overview

The dashboard is structured into **four pages**, each serving a distinct analytical purpose:

| Page | Route / Tab | Purpose |
|------|-------------|---------|
| **Home** | `Home` | Landing page & entry point |
| **Overview** | `Overview` | High-level summary & KPIs |
| **Artists** | `Artists` | Artist-focused deep dive |
| **Songs** | `Songs` | Song-level analysis & data table |

---

## 🏠 Page 1 — Home

![Home Preview](https://github.com/Rajni0327/Power-BI-Spotify-Analytics-Dashboard/blob/main/Home%20page.png)


The **Home** page is the landing screen of the dashboard. It features:

- The **Spotify logo** prominently displayed as the central brand element.
- A clean navigation bar with links to all four dashboard sections: **Home**, **Overview**, **Artists**, and **Songs**.
- A background collage of album art that creates visual depth and atmosphere, giving users an immediate sense of the music data being explored.

This page acts as the gateway — guiding users into the rest of the dashboard with minimal clutter.

---

## 📊 Page 2 — Overview

![Overview Preview](https://github.com/Rajni0327/Power-BI-Spotify-Analytics-Dashboard/blob/main/Overview%20page.png)

The **Overview** page delivers a bird's-eye view of the entire dataset through a mix of KPI cards, donut charts, and time-series visualizations.

### Key Metrics (KPI Cards)
- **789** Distinct Songs
- **342** Count of Artists
- **3.28 min** Average Song Duration
- **89.62** Average Popularity Score

### Charts & Visualizations

- **Songs by Album Type** *(Donut Chart)* — Breaks down the split between singles (269) and albums (562).
- **Explicit vs. Non-Explicit Songs** *(Donut Chart)* — Shows the ratio of explicit (~11K) to non-explicit (~17K) content.
- **Songs by Year** *(Donut Chart)* — Highlights the distribution across 2023 (423 songs) and 2024 (452 songs).
- **Avg Popularity by Album Type** *(Donut Chart)* — Compares average popularity across singles (35.82%), albums (34%+), and compilations (29.74%).
- **Songs by Artist** *(Horizontal Bar Chart)* — Top artists ranked by distinct song count. Taylor Swift leads with **85** songs, followed by Travis Scott (30), Drake (27), Bad Bunny (22), and others.
- **Songs by Artist — Popularity** *(Horizontal Bar Chart)* — Top songs ranked by total popularity score, with *"I Wanna Be Your Dog"* topping at **51K** and *"Cruel Summer"* at **50K**.
- **Avg Popularity by Month** *(Line Chart)* — Tracks monthly popularity trends across the year, showing a dip around September–October before recovering in November–December.
- **Distinct Songs by Month** *(Bar Chart)* — Visualizes song release volume per month. October peaks at **220** distinct songs, followed by November (202) and December (212).

---

## 🎤 Page 3 — Artists

![Artists Preview](https://github.com/Rajni0327/Power-BI-Spotify-Analytics-Dashboard/blob/main/Artists%20page.png)

The **Artists** page zooms into artist-level performance with three dedicated chart panels and a detailed data table.

### Charts

- **Songs by Artist** *(Horizontal Bar Chart)* — Distinct songs per artist. 
- **Popularity by Artist** *(Horizontal Bar Chart)* — Total popularity aggregated by artist.  
- **Songs by Artist — Position 1 Hits** *(Horizontal Bar Chart)* — Artists ranked by number of #1 position hits.
  
### Data Table

The scrollable table at the bottom includes per-song details:

| Column | Description |
|--------|-------------|
| `song` | Song title |
| `release_date` | Original release date |
| `album_type` | Single or Album |
| `Avg Popularity` | Average popularity score |
| `Max Popularity` | Peak popularity score |
| `Avg Duration Minutes` | Average track length in minutes |

---

## 🎶 Page 4 — Songs

![Songs Preview](https://github.com/Rajni0327/Power-BI-Spotify-Analytics-Dashboard/blob/main/Songs%20page.png)

The **Songs** page focuses on song-level and album-level analytics, combining three chart panels with a comprehensive data table.

### Charts

- **Songs by Artist** *(Horizontal Bar Chart)* — Distinct artists contributing songs, sorted by count. 
- **Songs by Popularity** *(Horizontal Bar Chart)* — Individual songs ranked by total popularity. 
- **Avg Track per Album** *(Horizontal Bar Chart)* — Average number of tracks per album, grouped by artist. 

### Data Table

The detailed table provides album-level artist analytics:

| Column | Description |
|--------|-------------|
| `artist` | Artist name |
| `album_type` | Album classification |
| `Distinct Songs` | Number of unique songs |
| `Albums Count` | Total albums in the dataset |
| `Hits per Artists` | Number of hit songs |
| `Avg Popularity` | Average popularity across songs |
| `Avg Tracks per Album` | Mean track count per album |
| `Total Songs` | Total song count |

Notable entries include Arctic Monkeys (548 total songs, 13 distinct), Ariana Grande (393 total songs, 13 distinct, 13 hits), and Bad Bunny (388 total songs, 21 distinct, 7 hits).

---

## 🎨 UI & Design Details

- **Theme:** Dark mode with Spotify's signature **green (#1DB954)** as the primary accent color.
- **Layout:** Sidebar with a scrollable artist/song list on the left; main content area on the right with charts and tables.
- **Music Player:** A persistent mini-player widget (bottom-right on inner pages) displaying the currently selected track with playback controls.
- **Navigation:** Top-right tab bar for switching between Home, Overview, Artists, and Songs.
- **Charts:** Horizontal bar charts, donut/pie charts, line charts, and column bar charts — all styled consistently with the dark theme.
- **Tables:** Scrollable data grids with clean column headers and alternating row readability.

---

## 📂 Data Columns Reference

| Field | Description |
|-------|-------------|
| `artist` | Name of the artist |
| `song` | Title of the song |
| `album_type` | Type: `album`, `single`, or `compilation` |
| `release_date` | Date the song/album was released |
| `Distinct Songs` | Count of unique songs by the artist |
| `Albums Count` | Number of albums by the artist |
| `Hits per Artists` | Songs that reached a top position |
| `Avg Popularity` | Mean Spotify popularity score |
| `Max Popularity` | Highest recorded popularity score |
| `Avg Tracks per Album` | Average tracks across all albums |
| `Total Songs` | Total song count in the dataset |
| `Avg Duration Minutes` | Average song length in minutes |

---

## 🚀 Getting Started

1. Open the dashboard application.
2. Land on the **Home** page.
3. Use the top navigation bar to explore:
   - **Overview** — for a quick summary of the entire dataset.
   - **Artists** — to drill down into specific artist performance.
   - **Songs** — to analyze individual songs and album-level stats.
4. Use the **left sidebar** to browse and select specific artists or songs.
5. The **mini player** updates based on your selection.

