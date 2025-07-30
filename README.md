# UFO Sightings Data Analysis (NUFORC Dataset)
📁 Overview
This project explores patterns in UFO sighting reports submitted to the National UFO Reporting Center (NUFORC) between the 1990s and early 2000s. Using Python and data visualization tools, I cleaned and analyzed the data to uncover trends in time, geography, and reported UFO shapes.


#  Objectives
- Clean and preprocess raw UFO report data

- Visualize the temporal and geographical distribution of sightings

- Analyze the types (shapes) of reported UFOs

- Identify anomalies and patterns in the data

- Present insights using clear and engaging visuals

# Dataset Description
The original dataset includes the following columns:

Occurred:	Date and time the sighting occurred
City:	City where the sighting took place
State:	U.S. state (if reported)
Shape:	Reported shape of the UFO (e.g., Disk, Light, Triangle)
Summary:	Short description of the sighting
Reported:	Date when the sighting was reported
Link, Media, Explanation	Misc. metadata, not used in analysis

# Data Cleaning Steps
- Converted date columns to datetime format

- Standardized and filtered U.S.-based reports

- Dropped rows with missing critical fields (e.g., city, date)

- Removed unnecessary metadata columns

- Normalized shape data for consistency (e.g., “circle” and “circular”)

#  Visualizations
- Sightings Over Time: Time series showing spikes in reports

- Top Cities/States: Bar charts for most common sighting locations

- UFO Shapes: Distribution of reported shapes over time

- Monthly/Hourly Patterns: Trends by month and hour of day

- Word Cloud: Common words used in sighting descriptions

#  Tools & Libraries
- pandas

- matplotlib & seaborn

- plotly (for interactive maps)

- wordcloud

- datetime

#  Key Insights

The most reported UFO shape was light, followed by circle and triangle.

Washington, California and Michigan had the highest number of reports.

Most sightings occured in Febuary 

Most sightings occurred on Thursdays.

Many sightings occur between 7:00p.m to midnight


