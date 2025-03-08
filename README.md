# COVID-19 Data Visualizations - South Korea

This project provides a dashboard with five different perspectives on the pandemic, from patient-infection relationships to regional trends and hierarchical distributions.

## Project Overview

This project aims to provide an interactive and informative dashboard for visualizing the COVID-19 pandemic's impact in South Korea. By utilizing D3.js, the visualizations offer a dynamic way to explore various aspects of the data, including infection networks, geographical spread, temporal trends, and hierarchical breakdowns. The dashboard is designed to be user-friendly, allowing users to easily filter, zoom, and drill down into the data to gain deeper insights.

## Visualizations

1. **Forced-Directed Graph:** Visualizes relationships between COVID-19 patient-infection cases, allowing users to explore connections across geographic regions.
2. **Map Representation of Cases:** An interactive map of South Korea showing the spread of cases across provinces.
3. **COVID-19 Infection Timeline:** A line graph displaying confirmed, released, and deceased cases over time.
4. **Hierarchical Tree Map:** A tree map showing the number of confirmed cases in regions (province and cities).
5. **Sunburst Chart:** Represents hierarchical data of COVID-19 cases in different age groups and genders.

## Features

* Interactive D3.js visualizations
* Zoom and pan functionality
* Filtering by region and case type
* Tooltips for detailed information
* Animated timelines
* Drill-down navigation for hierarchical data

## Usage

To run the visualizations locally, clone the repository and open the `dashboard.html` file in a web browser. Ensure you have a local server running to avoid CORS issues with loading data files.

```bash
git clone https://github.com/mohammad-malik/covid-visualizations-d3.git
cd covid-visualizations
open index.html
```

## Data Sources

The COVID-19 data used in these visualizations is primarily sourced from the [Korea Disease Control and Prevention Agency (KDCA)](https://www.kdca.go.kr/index.es?sid=a2). Additional geographic data for South Korea, used for the map visualization, is obtained from the [southkorea-maps](https://github.com/southkorea/southkorea-maps/tree/master) GitHub repository. The KDCA data was accessed and processed to create the visualizations.

## Technologies Used

* D3.js
* HTML/CSS
* JavaScript

## License

This project is licensed under the Apache-2.0 License. See the [LICENSE](LICENSE) file for details.
