# project_samarth-GIS-spatial

# Crime Data Visualization Project

This project processes and visualizes crime data for cities across India. It loads crime-related data, geocodes city names to geographic coordinates, and then generates an interactive map to visualize the crime locations on a map.

## Features

- **Data Loading**: Loads crime data from a CSV file (`crime_dataset_india.csv`).
- **Geocoding**: Converts city names to geographic coordinates (latitude and longitude) using the `geopy` library.
- **Data Merging**: Merges the original crime data with the geographic coordinates.
- **Map Creation**: Generates an interactive map using the `folium` library to visualize the crime locations.
- **Output**: Outputs the processed data into a new CSV file (`crime_with_coordinates.csv`) and an HTML file with the interactive map (`crime_map.html`).

## Prerequisites

Before running the project, ensure you have the following:

- **Python 3.6 or higher**
- **pip** (Python's package installer) for installing dependencies

## Setup Instructions

Follow these steps to set up and run the project:

### Step 1: Clone the repository

```bash
git clone https://github.com/ `````

