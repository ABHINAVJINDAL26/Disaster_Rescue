# 🌪️ Disaster Rescue Management System

An AI- and map-powered web application designed to assist in disaster reporting, rescue route planning, and coordination between citizens and rescue teams in real-time.

## 📌 Project Overview

In times of disasters like floods, earthquakes, landslides, and fires, timely communication and route planning can save lives. This system enables:

- Citizens to report disaster events with location and severity
- Rescue teams to visualize incidents on the map
- Dynamic route planning to reach affected areas quickly and safely
- Optional use of AI for severity prediction or crowdsource prioritization

## 🚀 Key Features

- 🗺️ **Interactive Map Interface**
  - Built using **Leaflet.js** with OpenStreetMap tiles
  - Live plotting of reported disaster zones

- 🆘 **Disaster Reporting Form**
  - Citizens can report:
    - Type of disaster
    - Location (auto or manual pin)
    - Description and images

- 🛣️ **Rescue Route Planner**
  - Finds optimal path using pathfinding algorithms (e.g., Dijkstra, A*)
  - Bypasses blocked/danger zones if data is provided

- 📸 **Image-Based Severity Detection (Optional AI)**
  - Integrate AI models to predict disaster severity from uploaded images

- 🧠 **Admin/Rescue Dashboard**
  - View all reports, locations, and assign rescue teams dynamically

## 🧰 Tech Stack

### Frontend
- **HTML, CSS, JavaScript**
- **Leaflet.js** for map rendering
- **Bootstrap** or **TailwindCSS** for responsive design

### Backend
- **PHP / Node.js / Python (Flask)** for API and form processing
- **MySQL / MongoDB** for storing user reports and routes
- **Java** for implementing pathfinding algorithms (Dijkstra, A*, etc.)

### Optional AI/ML
- **Python + OpenCV / TensorFlow** for image-based severity classification
- **Socket.IO** for live location updates and team status

## 📦 Project Structure

