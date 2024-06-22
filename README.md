# Ford GoBike Data Analytics Project
#### By - Noora Abubakar

## Table of Contents
- [Project Overview](#po)
- [Files Included](#fi)
- [Dataset](#dataset)
- [Project Steps](#ps)
  - [Data Collection](#dc)
  - [Data Cleaning](#clean)
  - [Exploratory Data Analysis](#eda)
  - [Data Visualization](#dv)
  - [Findings and Results](#far)
  - [Presentation](#present)
- [Key Insights for Presentation](#kip)
- [Conclusion](#con) 

## Project Overview  <a name="po"></a>

This project involves analyzing the Ford GoBike dataset to uncover insights about bike-sharing patterns, user demographics, and usage behavior. The analysis is conducted through data exploration, visualization, and modeling using Jupyter Notebooks.

## Files Included  <a name="fi"></a>

- **Ford_GoBike_slide_deck_II.html**: An HTML export of the project presentation slides.
- **Ford_GoBike_slide_deck_II.ipynb**: The Jupyter Notebook containing the analysis and visualizations for the project presentation.
- **Ford_GoBike_slide_deck_II.slides.html**: Another HTML export of the presentation slides.
- **fordgo_bike.csv**: The dataset containing the Ford GoBike data used for analysis.
- **Part_I_exploration_template.html**: An HTML export of the initial data exploration and analysis.
- **Part_I_exploration_template.ipynb**: The Jupyter Notebook containing the initial data exploration and analysis.
- **README.md**: This file.

## Dataset  <a name="dataset"></a>
The dataset, `fordgo_bike.csv`, contains detailed information on bike-sharing trips recorded by the Ford GoBike system. The dataset can be obtained through [Ford GoBike System Data](https://www.google.com/url?q=https://www.fordgobike.com/system-data&sa=D&ust=1554486256012000). 
Each entry represents a single trip and includes various attributes such as:

- **Trip Duration**: The total time taken for the trip.
- **Start Time and End Time**: Timestamps indicating when the trip began and ended.
- **Start Station and End Station**: The locations where the trip started and ended.
- **Bike ID**: A unique identifier for each bike used in the trips.
- **User Type**: Classification of the user as either a subscriber (regular user) or a customer (casual user).
- **User Demographics**: Additional user information including gender and year of birth.

This dataset provides a comprehensive view of user behavior and system usage, enabling in-depth analysis of temporal patterns, user demographics, and geographic trends in bike-sharing.

## Project Steps  <a name="ps"></a>

1. **Data Collection**: <a name="dc"></a>
   - The `fordgo_bike.csv` file was acquired, containing data on bike trips including start and end times, start and end stations, trip durations, bike IDs, user types, and more.

2. **Data Cleaning**: <a name="clean"></a>
   - Missing values were identified and handled appropriately.
   - Data types were corrected where necessary (e.g., converting date strings to datetime objects).
   - Irrelevant columns were dropped to streamline the analysis.

3. **Exploratory Data Analysis (EDA)**: <a name="eda"></a>
   - Initial insights were drawn using descriptive statistics and visualizations.
   - Patterns and anomalies in the data were identified and investigated further.
   - Key metrics such as trip duration, frequency, and user demographics were calculated and visualized.

4. **Data Visualization**: <a name="dv"></a>
   - Various plots were created to visualize bike usage patterns, such as:
     - Trip duration distributions.
     - User type comparisons.
     - Temporal patterns (e.g., usage by time of day, day of the week).
     - Geographic patterns (e.g., popular start and end stations).

5. **Findings and Results**: <a name="far"></a>
   - The analysis revealed that:
     - The majority of users were subscribers rather than casual users.
     - Peak usage times were during morning and evening commutes.
     - Certain stations were significantly more popular, indicating potential areas for service improvement or expansion.
     - Weekday usage was higher compared to weekends, aligning with commuter patterns.

6. **Slide Deck Presentation**: <a name="present"></a>
   - The key findings and visualizations were compiled into a slide deck (`Ford_GoBike_slide_deck_II.ipynb`) to communicate insights effectively.
   - The presentation was exported to HTML for easy sharing and viewing (`Ford_GoBike_slide_deck_II.html` and `Ford_GoBike_slide_deck_II.slides.html`).

## Key Insights from the Presentation  <a name="kip"></a>
A key insight from the analysis is that subscribers mainly use the Ford GoBike service during weekday morning and evening peaks, indicating a reliance on the service for commuting. In contrast, casual users have a more even distribution of usage throughout the day, with peaks on weekends, suggesting recreational use. This distinction highlights the need for targeted strategies: enhancing service during peak hours for commuters and offering promotions on weekends for recreational users

## Conclusion  <a name="con"></a>

This project provides a comprehensive analysis of the Ford GoBike dataset, revealing key insights into user behavior and system performance. The findings can be used to inform business decisions, improve service offerings, and enhance user experience.

---
