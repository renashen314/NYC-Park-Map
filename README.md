# 🌳 NYC Park Map

**NYC Park Map** is a web application that visualizes New York City's parks using interactive maps. It transforms raw park data into GeoJSON format and displays it on a user-friendly interface, making it easier for users to explore and learn about parks across the city.

Check out the demo: [NYC Park Map](renashen314.github.io/NYC-Park-Map/)

---

## Features

- **Interactive Map**: Navigate through NYC's parks with zoom and pan functionalities.
- **Data Transformation**: Converts raw JSON park data into GeoJSON using a Jupyter Notebook.
- **Responsive Design**: Ensures optimal viewing experience across various devices.

## Project Structure
- index.html: The main HTML file rendering the map.
- data/: Contains the GeoJSON data for NYC parks.
- json_to_geojson.ipynb: processes the raw park data and converts it into GeoJSON format, which is then utilized by the application to render the parks on the map.
- package.json: Lists project dependencies and scripts.
