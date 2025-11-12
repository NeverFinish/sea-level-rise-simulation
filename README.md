\# Asia Sea Level Rise Simulation



!\[GitHub Pages Status](https://img.shields.io/badge/GitHub%20Pages-Deployed-brightgreen)

!\[Leaflet Version](https://img.shields.io/badge/Leaflet-1.9.4-blue)



\## Project Overview

This project is developed based on the open-source Leaflet mapping library. It focuses on simulating the impacts of sea level rise on the Asian region, with integrated geographical features including rivers, lakes, and East Asian cities. The interactive interface allows users to toggle between different sea level scenarios for an intuitive visualization of flooded areas.



\## Core Features

| Module               | Description                                                                 |

|----------------------|-----------------------------------------------------------------------------|

| Sea Level Rise Simulation | Toggle between 4 sea level heights: 0m (original terrain), 5m, 50m, and 75m. The 5m flooded area uses a bright blue color for enhanced visibility. |

| Geographical Feature Overlay | Independently show/hide major Asian rivers (blue lines), lakes (light blue filled areas), and East Asian cities (red dots). |

| Interactive Operations | Zoom in/out and pan the map. Click on red city dots to display city names. |

| Display Scope        | Default center at Asia's geometric center (40°N, 85°E) with zoom level 3, fully covering the Asian continent and surrounding seas. |



\## Online Access Link

No downloads required—access directly via:  

\[https://neverfinish.github.io/sea-level-rise-simulation/](https://neverfinish.github.io/sea-level-rise-simulation/)



\## Local Deployment Guide (Backup Option)

If the online link is unavailable, run the project locally with these steps:

1\. Clone the repository to your local machine:  

&nbsp;  ```bash

&nbsp;  git clone https://github.com/NeverFinish/sea-level-rise-simulation.git

&nbsp;  ```

2\. Navigate to the project folder and ensure all files are in the root directory (no nested subfolders).

3\. Install Visual Studio Code (VS Code) and the "Live Server" extension.

4\. Right-click the `index.html` file and select "Open with Live Server" to launch automatically in your browser.



\## Technical Dependencies

\- Mapping Library: Leaflet 1.9.4 (open-source, lightweight, supports interactive map development)

\- Data Format: GeoJSON (standard geospatial data format for storing flooded areas, rivers, lakes, and city coordinates)

\- Hosting Platform: GitHub Pages (free static website hosting with HTTPS encryption)



\## Data Description

\- Flooded Area Data: Generated based on Asian terrain elevation models to simulate submerged regions at different sea level heights.

\- Geographical Feature Data: Includes coordinates of major Asian rivers, large lakes, and key East Asian cities to ensure geographical accuracy.



\## Author Information

\- Author: \[Your Full Name]

\- Student ID: \[Your Student ID]

\- Submission Date: \[YYYY-MM-DD]



\## Notes

\- Supported browsers: Chrome, Edge, Firefox (latest versions recommended).

\- Large file loading may take 1-2 seconds. Refresh the page and wait patiently if layers fail to display.

\- This project is for academic demonstration purposes only; data is for reference.



---



\### User Guide

1\. After opening the online link, use the "Sea Rise" panel to toggle between different flooded scenarios.

2\. Use the "GeoFeature" panel to show/hide rivers, lakes, and cities.

3\. Zoom in to view local details and click red city dots to see city names.

