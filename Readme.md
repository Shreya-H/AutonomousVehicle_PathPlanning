## README: Path Planning with Google Places API

### Overview

This Python script demonstrates path planning for a given location using the Google Places API and the A\* search algorithm. It fetches nearby places within a specified radius, constructs a graph representing the locations, and calculates the shortest path between a start and goal node.

### Dependencies

- requests
- math
- networkx
- matplotlib
- heapq
- time
- webbrowser

### Setup

1. **Obtain a Google Places API key:** Visit the Google Cloud Platform console to create a new project and enable the Places API. Generate an API key for your project.
2. **Replace placeholders:** Replace `'YOUR_API_KEY'` and `'YOUR_API_ENDPOINT_URL'` with your actual API key and endpoint.
3. **Specify location:** Modify the `latitude` and `longitude` variables to your desired location.
4. **Adjust radius:** Change the `radius` variable to control the search area around the location.
5. **Define start and goal nodes:** Manually set the `start_node` and `goal_node` variables to the desired nodes in the graph.

### Usage

1. Run the script.
2. The script will fetch nearby places, build a graph, and calculate the shortest path.
3. The graph will be visualized, and the shortest path will be highlighted.
4. The Google Maps URL for the shortest path will be generated and opened in a web browser.

### How it works

1. Fetches nearby places using the Google Places API.
[Nearby places](https://github.com/Shreya-H/AutonomousVehicle_PathPlanning/blob/main/images.txt/nearby_places.png)
2. Creates a graph with locations as nodes and distances as edge weights.
[Location_Graph](https://github.com/Shreya-H/AutonomousVehicle_PathPlanning/blob/main/images.txt/pathfinding_graph.png)
3. Applies the A* search algorithm to find the shortest path between the start and goal nodes.
[route_summary](https://github.com/Shreya-H/AutonomousVehicle_PathPlanning/blob/main/images.txt/user_interface_2.png)
4. Visualizes the graph and highlights the shortest path.
[Graph Visualization](https://github.com/Shreya-H/AutonomousVehicle_PathPlanning/blob/main/images.txt/graph_visualization.png)
5. Generates a URL for Google Maps to display the route and opens it in the default web browser.
[google_maps_route](https://github.com/Shreya-H/AutonomousVehicle_PathPlanning/blob/main/images.txt/route_found_map.jpg)



### Limitations

- Relies on the accuracy of the Google Places API data.
- Does not consider traffic conditions or other real-world factors.

### Potential Improvements

- Incorporate traffic data for more realistic path planning.
- Explore different pathfinding algorithms for comparison.
- Enhance visualization with interactive features.
- Optimize the code for performance.

**Note:** This script is for demonstration purposes and may require adjustments for production-level applications.

### Additional Considerations

- Consider error handling for API requests and graph construction.
- Provide clear instructions for users to obtain an API key and set up the environment.
