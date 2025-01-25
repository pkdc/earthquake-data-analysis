# Earthquake Analysis Project

This project analyzes earthquake data and visualizes various aspects of the data using Python and Jupyter Notebook.

The data set is taken from USGS(U.S Geological Survey). The USGS provides reliable scientific information to describe and understand the Earth; minimize loss of life and property from natural disasters; manage water, biological, energy, and mineral resources; and enhance and protect our quality of life.

As part of it's program, USGS monitors and reports on earthquakes, assesses earthquake impacts and hazards, and conducts targeted research on the causes and effects of earthquakes. The USGS provides real-time notifications, feeds and web services about earthquakes just after they happen. Further details can be found in the link below,

https://earthquake.usgs.gov/earthquakes/feed/

## Project Structure

- `all_month.csv`: The dataset containing earthquake data.
- `earthquake.ipynb`: Jupyter Notebook containing the analysis and visualizations.

## Analysis

The notebook performs the following analyses:

- Reads and cleans the earthquake data.
- Filters earthquakes with magnitude greater than or equal to 5.
- Extracts and processes the location data.
- Groups and counts earthquakes by location.
- Visualizes the data using various plots.

## Visualizations

The notebook generates the following visualizations:

- Histogram of earthquake magnitudes.
- Scatter plot of earthquake locations.
- Bar plot of Top 10 earthquake counts by location.
- Scatter plot of depth vs. magnitude.
