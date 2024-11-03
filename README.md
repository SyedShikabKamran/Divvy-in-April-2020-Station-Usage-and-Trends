# Divvy Trip Analysis

This project provides an exploratory analysis of Divvy bike-sharing ridership patterns in Chicago during April 2020. By analyzing the trip data, we uncovered key insights into peak usage times, popular stations, and rider preferences based on membership status.

## Project Overview
The analysis aimed to identify patterns in Divvy ridership, including:
- Peak usage days and times
- Popular start and end stations
- Differences in behavior between annual members and casual riders

These insights are valuable for understanding user behavior and can potentially help in optimizing station placement and improving service offerings.

## Key Findings
- **Peak Usage**: Weekends, particularly Sundays, had the highest number of rides.
- **Popular Stations**: Clark St & Elm St emerged as the most popular station for both starting and ending rides.
- **Rider Types**: Annual members took significantly more rides than casual riders, with members favoring St. Clair St & Erie St as a secondary option.

## Data
The dataset used for this analysis is the **Divvy Trips April 2020** data, which contains details about each ride, including:
- `ride_id`, `rideable_type`, `started_at`, `ended_at`
- `start_station_name`, `end_station_name`
- `member_casual` status indicating rider type (member or casual)

## Analysis Process
1. **Data Loading**: Loaded the dataset and converted `started_at` and `ended_at` columns to datetime format.
2. **Exploratory Analysis**:
   - **Peak Days**: Identified the days with the highest number of rides.
   - **Popular Start/End Stations**: Ranked stations based on frequency of use for starting and ending rides.
   - **Rider Type Analysis**: Compared ride frequencies and station preferences for members and casual riders.
3. **Visualizations**: Generated bar charts to display popular stations and peak days for clear, visual insights.

## Conclusion
This analysis offers valuable insights into Divvy’s ridership patterns:
- **High weekend ridership** indicates a recreational trend among casual users.
- **Clark St & Elm St** was the top choice for both starting and ending trips, suggesting high demand in that area.
- **Member Preferences**: Members showed a preference for specific stations, which could inform targeted station enhancements.
