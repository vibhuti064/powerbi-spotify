# 🎵 Spotify Data Analysis Dashboard

![Dashboard Screenshot](<Screenshot 2025-11-28 210625.png>)
## 📊 Dashboard Link

[View Live Dashboard](https://app.powerbi.com/groups/me/reports/073d741f-9e15-4427-8fce-7e0aa5d043a8/feb74e732e32955ae75c?experience=power-bi)
## 📌 Project Overview
This Power BI project provides an interactive and visual analysis of Spotify music data. The dashboard allows users to explore trending songs, artist popularity, and album characteristics through a dynamic user interface designed to mimic the aesthetic of the Spotify application.

The goal of this project was to transform raw music data into actionable insights regarding track popularity, release trends, and artist performance.

## 📊 Key Features
* **Dynamic Album Slide Show:** A custom-built, interactive slicer allowing users to browse songs via album artwork.
* **KPI Tracking:** High-level metrics displaying Total Songs, Distinct Artists, Average Popularity, and Total Tracks.
* **Advanced Filtering:** Slicers for filtering data by specific Artists, Songs, or Timeframes (Month/Year).
* **Trend Analysis:**
    * **Songs by Artist:** A bar chart visualizing the volume of tracks per artist.
    * **Popularity Trends:** Area charts showing average popularity fluctuations over time (Monthly/Quarterly).
    * **Album vs. Single:** Breakdown of release types (Album, Single, Compilation).
* **UI/UX Design:** A custom "Dark Mode" aesthetic using Spotify's brand colors (Green/Black) with custom navigation buttons and transparent visual backgrounds.

## 🛠️ Tech Stack
* **Tool:** Microsoft Power BI Desktop
* **Data Transformation:** Power Query (ETL)
* **Calculations:** DAX (Data Analysis Expressions) for measures (e.g., Avg Popularity, Distinct Counts).
* **Visualization:** Native Power BI visuals, Custom Slicers, and Shape styling.

## 📂 Data Structure
The project utilizes a dataset containing the following key attributes:
* **Track Name**
* **Artist Name**
* **Album Name & Cover URL**
* **Release Date**
* **Popularity Score (0-100)**
* **Duration (ms)**
* **Album Type (Single/Album)**

## ⚙️ Process & Methodology
1.  **Data Import & Cleaning:** Loaded raw data into Power Query, handled missing values, and ensured correct data types (specifically for Date and Image URL fields).
2.  **Data Modeling:** Created a Calendar table for time-intelligence analysis and established relationships between data tables.
3.  **DAX Calculations:** Created calculated measures for dynamic aggregations (e.g., `Average Popularity`, `Track Count`).
4.  **Dashboard Design:** * Implemented a canvas background designed in Figma/PowerPoint.
    * Utilized the **Image Tile Slicer** technique to create the central album art navigation.
    * Applied transparent backgrounds to visuals to blend seamlessly with the dark theme.

## 🚀 How to Use
1.  **Download:** Clone this repository or download the `spotify.pbix` file.
2.  **Open:** Open the file in **Microsoft Power BI Desktop**.
3.  **Interact:**
    * Use the central **Album Art Slider** to filter the dashboard by a specific song.
    * Click on **Artist names** in the bar charts to cross-filter other visuals.
    * Use the **Date Hierarchy** buttons (Month/Quarter) to change the granularity of the trend graphs.

## 🤝 Credits
* **Dataset:** [https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset]


