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
git clone https://github.com/TanyaRauthan/MapGenius.git
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

Set up a React project: If you don't already have one, create a new React project using Create React App or a similar tool:

Bash

npx create-react-app my-map-app
cd my-map-app
Install dependencies: Install the necessary packages:

Bash

npm install react-leaflet leaflet react-geolocated
# Or if you use yarn:
yarn add react-leaflet leaflet react-geolocated
You'll also need your UI component library (the one that provides Card, Input, Select, Button, etc.).  I can't know which library you're using, but it might be something like shadcn/ui, material-ui, antd, or similar. Install that as well, following its instructions.  For example, if it's shadcn/ui:

Bash

npx shadcn-ui@latest init
Replace the contents of src/App.js (or your main component file) with the code I provided: Copy and paste the improved MapGeniusComponent code into your App.js file (or whichever file you want to put it in).

Import your UI components: Make sure you correctly import the UI components (Card, Input, Select, Button, etc.) at the top of your component file. The paths I used in the example /components/ui/... are placeholders.  Adjust these paths to match your project structure.  For instance:

JavaScript

import { Card, CardContent, CardHeader, CardTitle } from "@/components/ui/card"  // Example using @ alias
import { Input } from "@/components/ui/input"
import { Label } from "@/components/ui/label"
import { Button, Select, SelectContent, SelectItem, SelectTrigger, SelectValue } from "@/components/ui/select"
Run the development server:

Bash

npm start
