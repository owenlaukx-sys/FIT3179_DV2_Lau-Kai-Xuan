# FIT3179_DV2_Lau-Kai-Xuan
My FIT3179 (Data Visualisation) Project / Data Visualisation 2 GitHub Repository consisting of the webpage application files, chart design files and all used datasets. 

**Topic**: Cultural Events
**Description**: Investigate publicly available datasets on cultural events across Australia. Compare event types, locations, frequency over time to explore Australia's cultural landscape

## Project Structure
```
FIT3179_DV2_Lau-Kai-Xuan
├── /data
├── /js
    ├── /maps
├── index.html
├── styles.css
```

/data - Contains all CSV files as the primary data folder of the project \
/js - Contains all webpage Vega-lite chart components and maps, with `Australian_Cultural_Events_List_2026.csv` being the main original dataset \
/maps - A folder within /js that contains all the maps used in the visualisation

## Data Description
Our main data source is stored in the `Australian_Cultural_Events_List_2026.csv` which will only cover certain events from year 2026, since there's no single unified dataset found that is small-scaled enough to be usable for the purposes of this assignment. The dataset CSV has 15 columns that record the Event Name, Start Date, End Date, Event City, State, Venue, Description, Event Category, Starting Month, Duration and the corresponding location related latitudes and longitudes for the city and 'exact' venue (some events found don't have a single venue, but are spread out around a city). The sources for all of these events are also provided in a dedicated column within the dataset. 

## Charts Included and Themes
The visualisation will explore the where, what and when about Australian cultural events. These could span from sporting events to parades, indigenous festivals, film festivals, art exhibition events and more, documenting the unique local cultures in Australia and its international presence in promoting the performing arts and human achievements. The 12 charts that form part of our visualisation includes: 

### 5 Map charts 
1. Host Cities or Localities Map of Where Events are Held (*Proportional Symbol Map*)
2. State Map for Proportion of the Total Events Recorded (*Choropleth Map*)
3. Map of Sydney Area Events Location (*Dot Map*)
4. Map of Adelaide Area Events Location (*Dot Map*)
5. Map of Melbourne Area Events Location (*Dot Map*)

### Other Charts
1. Top 6 Cities with the Largest Cultural Event Numbers in Australia 2026 (*Bar Chart*)
2. Donut Chart for Categories of Events (*Donut Chart*)
3. Event Categories by State Bar Chart (*Stacked Bar Chart*)
4. Monthly Calendar Heatmap of Event Density throughout Year 2026 (*Calendar Heatmap*)
5. Secondary Comparison Chart for Number of Events Recorded by State (*Lollipop Chart*)
6. Top 6 Longest-Running Events Duration of the Year 2026 (*Gantt Chart*)
7. Distribution of Arts, Sports and Aboriginal / Indigenous Events across States (*Radar Chart*)

### Idioms
As a summary of the idioms used within this data visualisation, DV2 uses: 

1. Proportional Symbol Map
2. Choropleth Map
3. Dot Map
4. Bar Chart
5. Donut Chart
6. Stacked Bar Chart
7. Calendar Heatmap
8. Lollipop Chart
9. Gantt Chart
10. Radar Chart