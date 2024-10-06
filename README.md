# belly-button-challenge
# Belly Button Biodiversity Dashboard

## Overview

This project is an interactive dashboard that visualizes the Belly Button Biodiversity dataset. The dataset catalogs the microbes that colonize human navels and reveals that a small handful of microbial species were present in more than 70% of individuals, while the rest were relatively rare.

This dashboard allows users to explore the dataset by selecting different individuals from a dropdown menu. The following visualizations are dynamically updated when a new sample is selected:

- A **horizontal bar chart** showing the top 10 operational taxonomic units (OTUs) for the selected sample.
- A **bubble chart** showing the distribution of OTUs in the selected sample.
- A **demographic panel** displaying metadata about the selected individual.

## Features

- **Dropdown Menu:** Select from different individuals (samples) to explore.
- **Bar Chart:** Displays the top 10 OTUs for the selected individual.
- **Bubble Chart:** Shows the frequency and diversity of OTUs in each sample.
- **Metadata Panel:** Displays demographic information for the selected individual.

## Dataset

The dataset used for this project is provided from the following URL:

[https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json)

The dataset contains the following fields:
- **names:** A list of sample IDs.
- **metadata:** Demographic information for each individual.
- **samples:** Microbial data for each sample including `otu_ids`, `otu_labels`, and `sample_values`.

## How to Run the Project

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/widchy95/belly-button-challenge.git
    ```

2. Navigate to the project folder:

    ```bash
    cd belly-button-challenge
    ```

3. Open the `index.html` file in your web browser to view the dashboard:

    ```bash
    open index.html
    ```

## Deployment

The project is deployed using GitHub Pages. You can view the live dashboard here:

[Live Dashboard on GitHub Pages](https://widchy95.github.io/belly-button-challenge)

## Usage

- Select a sample from the dropdown menu to display the corresponding data.
- Hover over the bar chart to see OTU labels.
- Hover over the bubbles in the bubble chart to view more detailed information about each OTU.

## Files in the Repository

- **index.html** - Main HTML file for the dashboard.
- **static/js/app.js** - JavaScript code that builds the charts and handles interactions.
- **static/css/style.css** - Optional custom CSS for styling the dashboard.
- **samples.json** - The dataset used for the project (linked from an external source).
- **README.md** - This readme file.

## Technologies Used

- **D3.js** - For fetching and manipulating the data.
- **Plotly.js** - For creating interactive charts.
- **HTML/CSS/JavaScript** - To build and style the dashboard.
- **GitHub Pages** - For deploying the dashboard.

## Acknowledgements

This project was developed as part of a data visualization challenge. The dataset is provided by UC Berkeley as part of a larger microbiome study.

## Prepared by 

**Widchy Joachim**
*Data Analyst*
