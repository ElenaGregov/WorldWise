# 🌍 WorldWise

**WorldWise** is a React + Vite travel tracking app that lets users mark cities they’ve visited, view them on an interactive map, and keep notes using a user-friendly interface. The app integrates a mock backend powered by JSON Server to simulate real API interactions.

## 📌 Overview

Built as a practical project during a web development course, WorldWise emphasizes working with geolocation data, mapping libraries, and mock API services.

## 🚀 Features

- Select cities on an interactive map
- Add notes and visit dates to each city
- View all visited cities in a list or on the map
- Responsive UI design
- JSON Server as a mock backend

## 🛠️ Tech Stack

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [React Router DOM](https://reactrouter.com/)
- [Leaflet.js](https://leafletjs.com/) + [React Leaflet](https://react-leaflet.js.org/)
- [React Datepicker](https://reactdatepicker.com/)
- [JSON Server](https://github.com/typicode/json-server)


## 💻 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ElenaGregov/WorldWise.git
cd WorldWise

2. Install dependencies
```bash
npm install

3. Start the Vite dev server
```bash
npm run dev

4. Start JSON Server (mock API)
```bash
npm run server

This starts JSON Server at http://localhost:9000 using data/cities.json.

API endpoint:

bash
http://localhost:9000/cities

⚠️ Make sure to start JSON Server before using the app to ensure data loads correctly.

🧠 What I Learned:

- How to integrate Leaflet with React using React Leaflet

- Working with custom hooks and global context

- Managing data via mock APIs using JSON Server

- Structuring a real-world frontend project
