# Astro World (أسترو وورلد)

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge)](https://astrocoderseg.vercel.app/)
[![NASA Space Apps](https://img.shields.io/badge/NASA-Space%20Apps%20Challenge-0B3D91?style=for-the-badge)](https://www.spaceappschallenge.org/)
[![Team](https://img.shields.io/badge/Team-Astro%20Coders--EG-orange?style=for-the-badge)](#)

**Astro World** is an interactive, Arabic-first 3D space exploration and Mission Control web platform designed to make astronomy, planetary science, and aerospace engineering accessible and exciting for children and young learners. Built by **Astro Coders-EG** for the **NASA Space Apps Challenge**, the platform combines real-time space agency datasets, hands-on 3D simulations, and an interactive AI guide into an immersive browser experience.

---

## Live Preview

Explore the platform live here: **[https://astrocoderseg.vercel.app/](https://astrocoderseg.vercel.app/)**

---

## Key Features & Interactive Simulations

### 1. Mission Control Onboarding & NASA ASTRO AI Companion
* **Crew Check-In:** Users register their details upon entry to officially join the space mission.
* **Interactive AI Guide ("Astro"):** A persistent astronaut assistant located in the Mission Control sidebar featuring an active status indicator, live dialogue box, educational facts, and contextual prompts to guide young explorers throughout their journey.

### 2. Cosmic Launch Sequence (`MISSION-GALAXY-01`)
* A cinematic launch module featuring live NASA mission telemetry indicators and a space-time warp sequence that transitions users from Earth into deep space exploration.

### 3. 3D Solar System & Milky Way Explorer
* **Interactive Controls:** Orbit freely around the Milky Way, drag to rotate planets, scroll to zoom, and click on any celestial body to fly toward it.
* **Scientific Telemetry:** Selecting any planet reveals a real-time data card displaying its classification (e.g., Rocky Planet), surface gravity, average temperature, moon count, orbital period, and historical exploration milestones.

### 4. ISS 3D Space Mission (Interactive Game)
A first-person/free-roam 3D simulation placing players inside the **International Space Station** across **6 distinct modules** to complete real astronaut challenges:
* **Space Debris Defense:** Monitor and protect the station from incoming orbital debris hazards.
* **Space Botany (Space Lettuce):** Cultivate lettuce in microgravity, simulating NASA's Veggie plant growth experiments.
* **Life Support & Oxygen Repair:** Troubleshoot and repair critical oxygen generation and life-support systems.

### 5. NASA Live API & Deep Space Archive
* Direct integration with NASA's open archives to fetch and display ultra-high-resolution telescope captures (e.g., Hubble & James Webb) complete with official NASA IDs, capture dates, space center credits, and scientific descriptions.

### 6. NASA Science Hub (`science.html`)
* A dedicated educational documentation portal linking in-game 3D missions directly to real-world physics, space biology, and aerospace engineering principles.

---

## Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Animations & Glassmorphism UI), Vanilla JavaScript (ES6+)
* **3D Graphics & Rendering:** HTML5 Canvas & Custom 3D Engine (`astro-3d.js`)
* **Backend & Database:** Supabase
* **Space Data APIs:** NASA Open APIs & Canadian Space Agency (CSA) Datasets
* **Hosting & CI/CD:** Vercel

---

## Project Structure

```text
astro-world/
├── index.html          # Main Mission Control & 3D Exploration Gateway
├── science.html        # NASA Science Documentation & Educational Hub
├── css/                # Stylesheets, animations, and responsive layouts
├── js/
│   ├── astro-3d.js     # 3D Solar System & ISS rendering engine
│   └── ...             # API integrations, UI logic, and Astro companion
└── assets/             # Logos, 3D textures, astronaut avatars, and media
