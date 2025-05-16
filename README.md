# Leaflet Earthquake Visualization Module 15
 
An interactive web map built with Leaflet.js and D3.js that visualizes earthquake data from the USGS GeoJSON Feed. This project was completed as part of a data visualization challenge in the UC Berkeley Data Analytics Bootcamp.
 
---
 
## Table of Contents
 
- About the Project
- Technologies Used
- Features
- Project Structure
- Installation & Usage
- Data Sources
- Screenshots
- Author
- License 
 -Acknowledgments 

 
##  About the Project
 
The US Geological Survey (USGS) provides rich earthquake data via a public API, but lacks an intuitive way to visualize this data. This application bridges that gap, offering an interactive map that helps users understand global seismic activity through visual representation of magnitude and depth.
 
This project is divided into two parts:
- **Part 1:** Basic earthquake mapping with circle markers sized by magnitude and colored by depth.
- **Part 2:** Overlay tectonic plate boundaries and include layer controls with multiple basemap options.
 
---
 
##  Technologies Used
 
- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- [Leaflet.js](https://leafletjs.com/) – for map rendering
- [D3.js](https://d3js.org/) – for data loading and parsing
- [OpenStreetMap](https://www.openstreetmap.org/) – for base map tiles
- [OpenTopoMap](https://opentopomap.org/) – for topographic map tiles 
## Project Structure
 
leaflet-challenge/
├── Leaflet-Part-1/
│ ├── index.html
│ └── static/
│ ├── css/
│ │ └── style.css
│ └── js/
│ └── logic.js
│
├── Leaflet-Part-2/
│ ├── index.html
│ └── static/
│ ├── css/
│ │ └── style.css
│ └── js/
│ └── logic.js
 
---
 
##  Installation & Usage
 
### Clone the Repository
```bash
git clone https://github.com/Arisleyda02/leaflet-challenge.git
cd leaflet-challenge

**Run the App**
Open the Leaflet-Part-1/index.html or Leaflet-Part-2/index.html file in your browser.
(Optional) Run a local server if needed:
python -m http.server
Navigate to http://localhost:8000 to view the map.

**** Data Sources***
USGS Earthquake GeoJSON Feed
Fraxen's Tectonic Plates GeoJSON

