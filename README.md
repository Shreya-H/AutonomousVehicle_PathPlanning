# AutonomousVehicle_PathPlanning

__Introduction:__

PathPlanner-AStar-GoogleMaps is a project focused on optimizing routes and navigation, developed using Python. It utilizes the A* algorithm to determine the shortest path between two locations and integrates with the Google Maps API to retrieve nearby points of interest. The project features functionality for visualizing the pathfinding process and the route on Google Maps, offering a detailed and interactive approach to route planning.

__Features:__

1. Fetches nearby places from Google Maps based on latitude, longitude, and radius.
2. calculates the shortest path using the A* algorithm.
3. visualizes the graph with NetworkX and Matplotlib.
4. Generates a Google Maps URL for the calculated path and opens it in a web browser.

__How It Works:__

1. API Integration:
Uses the Google Maps API to fetch places within a specified radius of a given location.

2. Graph Creation:
It builds a graph where nodes represent locations, and edges represent the distance between them.

3. Pathfinding:
Implements the A* algorithm to find the shortest path between a user-specified start node and goal node.

4. Visualization:
Visualizes the graph and the shortest path using NetworkX and Matplotlib.

5. Google Maps URL Generation:
Generates a URL for Google Maps to display the route and opens it in the default web browser.

![User Interface](https://github.com/Shreya-H/AutonomousVehicle_PathPlanning/raw/main/images/user_interface.png)
