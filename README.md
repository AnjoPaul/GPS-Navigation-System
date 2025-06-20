Graph-Based GPS Navigation System


📜 Project Description
This project is a command-line based GPS Navigation System implemented in Python. It models a road network as a graph, where locations are vertices and routes are weighted edges.
The system leverages graph algorithms, primarily Dijkstra's, to compute the shortest path between two locations, considering factors like distance and traffic.

It features a dual-interface system:
An Admin Panel for managing the map's structure, including adding/deleting locations, updating traffic conditions, and noting roadside amenities.
A User Panel for finding, visualizing, and analyzing routes, including support for intermediate stops and searching for amenities along the way.
The project uses pickle for data persistence, saving the current state of the graph so that all changes are retained across sessions.

✨ Key Features
👨‍💼 Admin Features
Password Protected: Secure access to administrative functions (default password: admin).
Manage Graph: Add or delete places (vertices) from the map.
Update Routes: Add new routes (edges) with distance and initial traffic data.
Live Traffic Updates: Modify the traffic factor on any existing route to simulate real-time conditions.
Add Amenities: Add points of interest like "Hotel", "Restaurant", or "Petrol Pump" to specific routes.
Visualize Map: View the entire map network with labels for distance and traffic.

🚶 User Features
Shortest Path Calculation: Find the most efficient route from a source to a destination using Dijkstra's algorithm.
Multi-Stop Routes: Plan a journey with one or more intermediate stops.
Route Visualization: See the calculated shortest path highlighted on a graphical representation of the map.
Map Viewing: Display the map with options to show/hide 
Amenity Finder: After calculating a route, search for specific types of amenities (hotels, petrol pumps, etc.) available along that path.
Route Analytics: Get the total distance and estimated travel time for your journey.

