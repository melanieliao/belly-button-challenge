# Belly Button Biodiversity Dashboard

## Overview

This project is an interactive dashboard that visualizes microbial biodiversity data collected from different individuals. The dashboard includes:

A dropdown menu to select an individual's sample.

A horizontal bar chart displaying the top 10 OTUs found in that sample.

A bubble chart showing the distribution of all OTUs in the sample.

A metadata panel displaying demographic information about the individual.

## Features

Dropdown Selection: Users can select different samples from the dropdown to update the charts and metadata panel.

Bar Chart: Displays the top 10 OTUs found in the selected sample.

Bubble Chart: Provides a visual representation of all OTUs in the sample, with marker size representing sample values and color representing OTU IDs.

Metadata Panel: Displays demographic information such as age, location, and frequency of washing.

## Technologies Used

JavaScript (D3.js & Plotly.js): Used for data fetching and visualization.

HTML & CSS (Bootstrap): Provides structure and styling for the dashboard.

## How It Works

Fetching Data: The dashboard retrieves microbial data from a JSON file hosted online.

Dropdown Population: The sample IDs are dynamically populated into the dropdown menu.

Visualization Updates: When a new sample is selected, the metadata panel, bar chart, and bubble chart update accordingly.

Metadata Display: Key-value pairs from the JSON metadata object are looped through and displayed in the panel.

## Setup Instructions

Clone or download the project files.

Ensure the index.html file is opened in a browser.

The app.js file should be properly linked and referenced in the HTML script section.

Ensure internet access to load external libraries (D3.js & Plotly.js).

## File Structure

index.html – Main structure of the dashboard.

app.js – Contains JavaScript code for data fetching, visualization, and interactions.

samples.json – Contains the microbial data (loaded externally in this project).
