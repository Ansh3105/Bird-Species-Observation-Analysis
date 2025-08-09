🐦 Bird Species Observational Dashboard

📌 Overview
This project provides a comprehensive observational analysis of bird species, focusing on species diversity, population counts, and conservation watchlist status. The interactive Power BI dashboard integrates location-based sightings, temperature impact analysis, and species identification methods to help conservationists, researchers, and bird enthusiasts make data-driven decisions.

📊 Dashboard Features
1. Key Metrics
127 Unique Species

17,080 Total Bird Sightings

1,486 Flyover Sightings

23.44°C Average Temperature

2. Top 5 Species Under Watchlist (At Risk)
Bar chart displaying the most observed species on the PIF (Partners in Flight) Watchlist:

Cardinalis cardinalis

Thryothorus ludovicianus

Vireo olivaceus

Baeolophus bicolor

Passerina cyanea

3. Bird Observation Geo Data
An interactive map showing bird sighting locations across Maryland, Virginia, and Washington D.C.

4. Temperature Impact Analysis
Scatter plot visualizing the relationship between temperature and bird counts, segmented by habitat type (Forest vs Grassland).

5. % of Birds Under Watchlist
Donut chart showing watchlist vs non-watchlist species distribution.

6. Types of Identification Method
Donut chart categorizing bird sightings by Singing, Calling, and Visual Observation.

7. Species Richness by Location
Horizontal bar chart comparing species diversity in Forest and Grassland habitats, with a watchlist breakdown.

📂 Files in This Repository
Bird_Analysis_Dashboard.pbix → Power BI dashboard file.

bird_analysis_PowerBI_dashboard.png → Dashboard screenshot preview.

Bird_Analysis.ipynb → Jupyter Notebook for preprocessing and analysis.

🛠️ Tech Stack
Power BI → Data visualization and dashboard creation.

Python (Pandas, Matplotlib, Seaborn) → Data preprocessing & exploration.

Jupyter Notebook → Analytical workflow documentation.

📊 Data Source
The bird observation data used in this project originates from field survey datasets and conservation monitoring programs.
Primary reference sources include:

eBird – Global bird observation database.

Partners in Flight (PIF) – Watchlist and species conservation status.

Local environmental and wildlife survey records from Maryland, Virginia, and Washington D.C.

The dataset includes:

Species Information – Scientific name, habitat type, and conservation status.

Observation Records – Count, date, location, and temperature at time of observation.

Identification Method – Singing, calling, or visual confirmation.

🚀 How to Use
Open in Power BI

Load Bird_Analysis_Dashboard.pbix in Power BI Desktop to explore the dashboard interactively.

Run Python Analysis

Open Bird_Analysis.ipynb in Jupyter Notebook or VS Code.

Install dependencies:

bash
Copy
Edit
pip install pandas matplotlib seaborn
Execute cells for preprocessing, summary stats, and visualizations.

View Dashboard Screenshot

See bird_analysis_PowerBI_dashboard.png for a quick preview.

🎯 Insights from Analysis
The Forest habitat hosts slightly fewer unique species than Grassland but has more watchlist species.

Temperature influences sightings, with higher counts at moderate temperatures.

Majority of identifications are from Singing (38.43%) followed by Calling (34.9%) and Visual methods (26.67%).

📌 Future Improvements
Add seasonal migration trend analysis.

Integrate real-time bird tracking data from APIs.

Expand geographic scope beyond the current observation region.

📜 License
This project is released under the MIT License – feel free to use, modify, and share.
