# Geograpical-Routing-OSM
Overview
This Python-based geographic mapping tool calculates and visualizes driving routes between two user-specified locations. The application fetches geographic coordinates for input locations, determines the optimal driving route between them, and generates an interactive map displaying the route with distance and duration information.

Key Features:
 - Converts location names to geographic coordinates using OpenStreetMap geocoding
 - Calculates optimal driving routes using the OpenRouteService API
 - Computes straight-line and driving distances between locations
 - Generates interactive maps with route visualization
 - Automatically adjusts map zoom level based on distance
 - Saves results as self-contained HTML files for easy sharing

Technical Implementation
 - The tool is implemented in Python using several key libraries:
 - Folium for interactive map generation and visualization
 - Geocoder for location coordinate lookup
 - OpenRouteService Python client for route calculations
 - Requests for API communication
 - Geopy for distance calculations


The application handles the complete workflow from user input to map generation:
 1 - Accepts location names as text input
 2 - Converts locations to latitude/longitude coordinates
 3 - Calculates the optimal driving route between points
 4 - Generates an interactive map with route visualization
 5 - Saves the map as an HTML file


* Usage:
To use the tool:
    - Install required dependencies
    - Run the Python script
    - Enter two location names when prompted
    - View the generated map.html file
    - The output includes:
    - Visual representation of the route
    - Markers for start and end points
    - Calculated driving distance and duration
    - Interactive map controls for panning and zooming


Requirements
 - Python 3.7 or higher
 - Internet connection for API access
 - OpenRouteService API key (free tier available)
 

This tool is suitable for trip planning, logistics analysis, and educational purposes in geospatial applications. The modular design allows for easy extension to support additional mapping features or transportation modes.