
#  Earthquake Map Project


This project aims to create an interactive map displaying earthquake data retrieved from a GeoJSON API using leaflet. The map will include various features and functionalities as outlined in the rubric.


## Tools Used

This project was built using the following tools and technologies:

D3 Library: Leaflet (Data-Driven Documents) is a powerful JavaScript library for data visualization on the web. It was used to create the interactive maps in this project.

JavaScript: JavaScript is the primary programming language used for creating the interactivity and functionality of the web page.

HTML and CSS: HTML was used for structuring the web page, and CSS was used for styling.

GitHub: The project is hosted on GitHub, which allows for version control, collaboration, and sharing.## Features
## Features and Requirements

### TileLayer

- The project must load a TileLayer without any errors to serve as the base map.

### Connect to GeoJSON API using D3

- The application should successfully connect to a GeoJSON API using D3 without any errors to fetch earthquake data.

### Markers with Size Corresponding to Earthquake Magnitude

- Earthquake markers should vary in size based on their magnitude, allowing users to easily gauge the earthquake's strength.

### Legend Showing Depth and Corresponding Color

- A legend must be included to visually represent earthquake depth using different colors. The legend should clearly indicate the depth range for each color.

### Data Points

#### Data Points Scale with Magnitude Level

- Earthquake marker size should scale with the earthquake's magnitude. Larger markers should represent higher magnitude earthquakes.

#### Data Points Colors Change with Depth Level

- Earthquake markers' colors should change based on the depth level of each earthquake. Different depth ranges should be associated with distinct colors, as shown in the legend.

#### Tooltip with Magnitude, Location, and Depth

- Each earthquake marker should have a tooltip that displays the following information when users hover over or click on a data point:
  - Magnitude
  - Location
  - Depth

#### Correct Loading of Data Points

- Ensure that all earthquake data points load in their correct geographical locations on the map. There should be no misplaced or missing data points.

## Project Structure

- Organize the project's codebase for clarity, documentation, and ease of maintenance.

## Testing

- Thoroughly test the application to confirm that it meets the requirements specified in this README. Test various earthquake scenarios to ensure accurate visualizations and interactions.

## Conclusion

The Earthquake Map project aims to provide an informative and visually appealing map displaying earthquake data with the specified features and functionalities.

## Deployment

Link for the webpage: https://ashlingeorge.github.io/leaflet-challenge/


## Authors

- [Ashlin Shinu George](https://github.com/ASHLINGEORGE)


## Acknowledgements

Leaflet library , UNC Chapel Hill Bootcamp Datasource

I would like to thank the Leaflet library and the data source for making this project possible.