# WorldWise — Travel Tracker App

![WorldWise Demo](demo.gif)

**React + Vite travel tracking app**  
Mark cities you've visited, add notes & dates, explore on an interactive map

[Live Demo](https://worldwise-eg.netlify.app) • [Frontend](https://github.com/ElenaGregov/WorldWise) • [Backend](https://github.com/ElenaGregov/WorldWise---server)

---

## Overview

> **Course-based project** from Jonas Schmedtmann (Udemy)  
> **My contributions:** full deployment, stack upgrade, bug fixes, mobile responsiveness, separate backend

WorldWise lets users:
- Click anywhere on the map to add a city
- Add visit dates and personal notes
- View all trips in a list or on the map
- Work offline with persistent data

---

## Features

- Interactive map with **Leaflet + React Leaflet**
- Add / edit / delete cities
- Date picker via **React Datepicker**
- Fully responsive (mobile-first)
- Mock REST API with **JSON Server**

---

## Tech Stack

| Technology       | Badge |
|------------------|-------|
| React            | ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) |
| Vite             | ![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62A) |
| React Router     | ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white) |
| Leaflet          | ![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white) |
| JSON Server      | ![JSON Server](https://img.shields.io/badge/JSON_Server-000000?style=for-the-badge&logo=json&logoColor=white) |

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/ElenaGregov/WorldWise.git
cd WorldWise
```

### 2. Install dependencies
```bash
npm install
```

### 3. Start the app
```bash
npm run dev
```

### 4. Start JSON Server (in a new terminal)
```bash
npm run server
```
> **API:** `http://localhost:9000/cities`  
> **Data:** `data/cities.json`  
>  
> **Warning: Start JSON Server before launching the app!**

---

## What I Learned & Improved

- Integrated **Leaflet** with React using **React Leaflet**
- Built **custom hooks** and **global context** for state management
- Managed data flow with **mock REST API (JSON Server)**
- Structured a **production-like frontend app**

### My Upgrades
- Deployed on **Netlify** with custom domain
- Updated to **React 18 + Vite 5**
- Fixed **geolocation issues on mobile**
- Enhanced **responsive design & UX**
- Separated backend into its own repo

---

## Live Demo

[https://worldwise-eg.netlify.app](https://worldwise-eg.netlify.app)

---

**Built by Elena Gregov**  
Prague, CZ • Open to **junior/mid frontend roles**
```
