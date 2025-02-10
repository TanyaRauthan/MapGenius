# MapGenius
MapGenius - Route Optimization System
Overview
MapGenius is a powerful and intuitive route-planning and optimization tool designed to enhance navigation efficiency. It allows users to plot waypoints, define a starting and ending location, and optimize routes based on either shortest distance or least cost. This tool is especially useful for travelers, logistics companies, and businesses managing deliveries across multiple locations.

Features
Dynamic Waypoint Management: Add, modify, and remove waypoints easily.
Airport-Based Navigation: Select from a list of major global airports for precise navigation.
Optimization Algorithms:
Nearest Neighbor Algorithm: Ensures efficient path selection based on proximity.
Least-Cost Optimization (Placeholder): Future integration for cost-based optimization.
Drag-and-Drop Interaction: Easily reposition waypoints on the grid for a custom route.
Map Scaling: Adjustable grid size to refine accuracy.
Real-time Route Cost & Time Calculation: Estimate total travel expenses and time required.
Interactive UI: A clean, user-friendly interface using React.js and modern UI libraries.
Installation & Setup
Prerequisites
Ensure you have the following installed:

Node.js (v16 or later)
npm or yarn
A modern browser (Google Chrome, Firefox, Edge, etc.)
Step 1: Clone the Repository
sh
Copy
Edit
git clone https://github.com/yourusername/MapGenius.git
cd MapGenius
Step 2: Install Dependencies
sh
Copy
Edit
npm install
or

sh
Copy
Edit
yarn install
Step 3: Start the Development Server
sh
Copy
Edit
npm run dev
or

sh
Copy
Edit
yarn dev
Step 4: Open in Browser
Visit http://localhost:3000 to access MapGenius.

How to Use
Select Locations

Choose a starting location from the dropdown list of airports.
Define a final destination.
Add Waypoints

Click on the map grid to add waypoints manually.
You can also select predefined waypoints from the airport list.
Optimize Route

Select optimization criteria:
Shortest Distance (default)
Least Cost (upcoming feature)
Click the Optimize Route button to calculate the best path.
Review Results

View the optimized route on the map.
Check total cost and estimated travel time.
Adjust & Re-optimize

Drag and reposition waypoints.
Remove unnecessary waypoints.
Re-run optimization for better results.
Technology Stack
Frontend: React.js, TypeScript
UI Components: shadcn/ui, Lucide-React
Algorithm: Nearest Neighbor for shortest path
State Management: React Hooks (useState)
Future Enhancements
✔️ Implement Dijkstra’s Algorithm for more accurate pathfinding.
✔️ Add real-world travel cost estimations based on flight and transport data.
✔️ Improve UI/UX with advanced mapping libraries (Leaflet.js, Google Maps API).
✔️ Integrate user authentication for saved routes
