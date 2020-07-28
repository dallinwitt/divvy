# Movements of Bikes in Chicago's Divvy Bike System
## Data Analysis and Visualization

#### Motivation:
Bikeshare systems have become not only commonplace, but critical to supporting the active transport capabilities of cities across the country and world. Divvy Bike in Chicago is one of the largest bikeshare systems in existence. Divvy is kind enough to publish their usage data, so the bulk of the data for this project came from the [Divvy Bike Website](https://www.divvybikes.com/system-data). 

The goal of this project was to visualize the movements of shared bikes through the Divvy Bike system in a way that was clear and intuitive for a lay reader. I wanted to use different methods to visualize both station-level and system-level movements.

#### Methods
I decided to visualize station-level bike movement using a Sankey diagram. There are hundreds of stations that can act as sources and destinations for a given bike, so I limited my visualization to the six most popular source and destination stations. 

To visualize the system-wise movement of bikes, I decided to use a chord diagram to show how bikes moved between the wards of Chicago. This tool has the added benefit of simultaneously visualizing not only inter-ward movement, but also the wards where Divvy Bike is most actively used. 

Many thanks to Shahin Rostami for his wonderful Python wrapper of the D3 chord diagram visualizer.

#### Outcomes
For the Sankey diagram, I visualized flows through station 192, which is the bike share station at Chicago's Union Station. The Sankey diagram showed that about a quarter of the bikes that come into station 192 come from one of six stations, and a similar ratio is followed by departing bikes.

The chord diagram conveyed in a simple and interactive way which wards were the most popular for divvy bike usage, and which wards were most "connected".
