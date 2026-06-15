# Seoul Land Use & Urban Forest Analysis

## Project Overview

This project visualizes land-use patterns and urban forest distribution in Seoul using OpenStreetMap (OSM) data and Python-based GIS analysis tools.

The main objective is to analyze the spatial relationship between urban forests and major land-use types and to evaluate urban forest accessibility through buffer analysis. OpenStreetMap land-use data were collected and processed using GeoPandas, and the final results were implemented as an interactive web map using Folium.

---

## Objectives

- Visualize Seoul land-use distribution
- Identify urban forest locations
- Analyze urban forest accessibility using buffer analysis
- Compare spatial relationships between forests and surrounding land-use types
- Build an interactive Web GIS without commercial GIS software

---

## Data Source

### OpenStreetMap (OSM)

The project uses OpenStreetMap land-use data collected through OSMnx.

Collected land-use categories:

- Residential
- Commercial
- Industrial
- Forest

OpenStreetMap was selected because several external GeoJSON sources repeatedly returned 404 errors and could not provide stable access to up-to-date spatial data.

---

## Methodology

### 1. Data Collection

Land-use data were downloaded from OpenStreetMap using OSMnx.

### 2. Data Preprocessing

The collected spatial data were processed using GeoPandas.

Main preprocessing steps included:

- Land-use filtering
- MultiPolygon handling
- Coordinate Reference System (CRS) transformation
- GeoDataFrame integration

The analysis focused on four major land-use categories:

- Residential
- Commercial
- Industrial
- Forest

### 3. Buffer Analysis

To evaluate accessibility and spatial influence, buffer analysis was performed.

#### Urban Forest Buffer

- Extract forest features
- Generate a 500m buffer
- Merge overlapping buffers
- Create a citywide urban forest influence zone

The 500m distance was selected because it is commonly used in urban planning as a walkable neighborhood distance, representing approximately 5–10 minutes of walking time.

#### Additional Analysis (Version 2)

Additional buffer analysis was performed for:

- Commercial areas
- Industrial areas

This extension allows comparison between urban forest influence zones and other major land-use influence zones.

### 4. Interactive Web GIS

The final map was implemented using Folium.

Implemented functions include:

- Layer Control
- MiniMap
- Fullscreen Mode
- Distance Measurement Tool
- Mouse Coordinate Display
- Custom Floating Legend
- Interactive Tooltips

---

## Project Results

The analysis revealed that urban forests are not evenly distributed across Seoul and tend to be concentrated in specific areas.

The buffer visualization highlights areas with relatively high accessibility to urban forests and areas where access to green infrastructure may be limited.

The project demonstrates how open spatial data and Python GIS tools can be used to perform urban environmental analysis and develop Web GIS applications without proprietary GIS software.

---

## Version History

### Version 1

Features:

- Urban forest distribution visualization
- 500m urban forest buffer analysis
- Interactive Web GIS implementation

### Version 2

Additional features:

- Commercial area buffer analysis
- Industrial area buffer analysis
- Extended land-use accessibility comparison

---

## Technologies Used

- Python
- Google Colab
- GeoPandas
- Shapely
- Folium
- OSMnx
- OpenStreetMap
- GitHub Pages

---

## AI Assistance

This project utilized generative AI tools for:

- Python code development
- GIS workflow exploration
- Debugging
- Documentation support

Tools used:

- OpenAI ChatGPT (GPT-5.5)
- Google Gemini 2.5 Flash

Final implementation, validation, interpretation, and documentation were completed by the author.

---

## Interactive Web Map

### Version 1

https://yerin-0530.github.io/2026_seoul_forest_map/seoul_forest_map.html

### Version 2

(Insert Version 2 URL)

---

## Source Code

### GitHub Repository

https://github.com/yerin-0530/2026_seoul_forest_map

### Version 1 Notebook

https://github.com/yerin-0530/2026_seoul_forest_map/blob/main/seoul_forest_design_code.ipynb

### Version 2 Notebook

(Insert Version 2 Notebook URL)

---

## Author

Yerin

2026 Seoul Land Use & Urban Forest Analysis Project
