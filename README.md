# routMap

# 🗺️ Smart Route Optimizer

A powerful, interactive route optimization tool that helps drivers find the most efficient sequence to pick up and drop off passengers. Built with Leaflet.js and featuring real-time map visualization.

![Route Optimizer Demo](https://via.placeholder.com/800x400/1e2f2f/6abf8b?text=Route+Optimizer)

---

## ✨ Features

### 🚗 Core Functionality
- **Intelligent Route Optimization** - Automatically finds the shortest path using Nearest Neighbor algorithm
- **Real-time Map Visualization** - See your route instantly on an interactive map
- **Drag & Drop Support** - Reorder passengers manually with drag & drop
- **Geocoding Integration** - Search and pick addresses directly from the map

### 📍 Driver Management
- Set driver name and starting location
- Pick driver location directly from the map
- Remove driver with one click
- Visual status indicator (set/not set)

### 👥 Passenger Management
- Add passengers with name and address
- Pick passenger locations from the map
- Drag & drop to reorder passengers
- Remove individual passengers or clear all
- Demo data for quick testing

### 🗺️ Map Features
- Clean, minimal marker design with numbers
- Color-coded route segments
- Distance labels on each segment
- Interactive markers with popup information
- Auto-fit bounds to show all locations

### 📋 Itinerary Display
- Transparent, draggable itinerary panel
- Shows full route sequence with:
  - Driver start location
  - Each passenger stop with number
  - Segment distances
  - Total distance
- Full addresses displayed for each stop

### 📥 Export Options
- **Download PNG** - Save the map as a high-quality image
- **Download PDF** - Save the map as a PDF document (A4 landscape)
- Both exports include all map elements (markers, routes, itinerary, controls)

### 🎨 UI/UX
- Modern dark theme with glass-morphism effects
- Fully responsive design (works on desktop, tablet, and mobile)
- Smooth animations and transitions
- Clear status messages and feedback
- Intuitive button layouts

---

## 🚀 Quick Start

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari)
- Internet connection (for map tiles and geocoding)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/route-optimizer.git
cd route-optimizer
