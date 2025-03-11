# Road Analyzer (vibe-coded March 2025)

https://github.com/rogerlew/road-analyzer/

## Overview
Road Analyzer is a web-based application that allows users to analyze road paths and terrain characteristics. Users can draw road paths on a map and get detailed metrics including elevation profiles, grades, distances, and radius of curvature for each segment.

Live application: [https://rogerlew.github.io/road-analyzer/](https://rogerlew.github.io/road-analyzer/)

## Features
- Interactive map interface with terrain and satellite views
- Draw road paths directly on the map
- Automatic elevation data retrieval from USGS National Map API
- Conversion to UTM coordinates for accurate distance calculations
- Calculation of key metrics:
  - Point-to-point distances
  - Cumulative distances
  - Elevation changes
  - Road grades (%)
  - Radius of curvature
- Visual representation through interactive plots
- Export data as CSV or GeoJSON files

## How to Use
1. Open the application in your web browser
2. Click the "Draw Path" button to begin drawing a road path
3. Click on the map to create points along your desired path
4. Double-click to complete your path
5. Click "Run Analysis" to process the path
6. View the results table and plots in the modal window
7. Export the data using the CSV or GeoJSON buttons if needed

## Technical Details
Road Analyzer uses:
- Leaflet.js for mapping and drawing tools
- UTM coordinate conversion for accurate distance measurements
- USGS National Map API for elevation data
- Plotly for interactive data visualization
- Bootstrap for UI components

## Liability Disclaimer
**IMPORTANT**: Road Analyzer and all associated data, calculations, and analysis are provided "as is" for informational purposes only, without warranty of any kind, express or implied. The creators and contributors of Road Analyzer make no representations or warranties regarding the accuracy, completeness, reliability, or suitability of this application.

Users are solely responsible for any decisions or actions taken based on information provided by Road Analyzer. The elevation data comes from third-party sources and may contain inaccuracies. Road grade and curvature calculations are approximations and should not be relied upon for critical engineering, navigation, or safety decisions.

By using Road Analyzer, you agree that the creators and contributors shall not be liable for any direct, indirect, incidental, special, or consequential damages arising from the use of or inability to use this application.

## Feedback

Please contact rogerlew@uidaho.edu or use the [GitHub Issue Tracker](https://github.com/rogerlew/road-analyzer/)

## Dev

1. git clone https://github.com/rogerlew/road-analyzer
2. code .
3. serve `python -m http.server 8000`