# Thermal Radiation Interactive Simulation

An interactive web-based physics simulation designed for **Activity 1: Which Type of Surface Radiates More Infrared Radiation?** This educational tool allows students and teachers to run a step-by-step accelerated simulation comparing the cooling rates of hot water in three differently colored cans (black, white, and shiny silver/metal).

## Features

* **Step-by-Step Accelerated Simulation:** Simulate the 10-minute experiment one minute at a time. Each simulated minute runs in **4 real-time seconds**, giving students time to observe changes and record measurements without waiting 10 full minutes.
* **Live Digital Timer:** Visual countdown/count-up timer (`MM:SS`) with active status indicators synchronized with the data logging.
* **Dynamic Data Table:** Automatically logs temperature readings (°C) at each minute mark (0–10 minutes) with visual row highlighting when new data is recorded.
* **Real-Time Cooling Curve Graph:** Powered by **Chart.js**, plotting temperature vs. time across all three surfaces simultaneously to visualize heat loss rates.
* **Lab Guide & Safety Sidebar:** Displays the required apparatus and laboratory safety guidelines in an Arabic (RTL) interface.
* **Reset Control:** Easily reset the timer, table, and chart to repeat the experiment at any time.

## Scientific Concept

Based on **Newton's Law of Cooling** and thermal radiation principles:
* **Matte Black Can:** The best emitter of infrared radiation—loses heat the fastest (drops from 90.0°C to 43.6°C).
* **White Can:** Moderate emitter—cools at an intermediate rate (drops from 90.0°C to 58.4°C).
* **Shiny Silver/Metal Can:** Poor emitter (good reflector)—retains heat the longest (drops from 90.0°C to 76.3°C).

## How to Run

This project is built as a single standalone HTML file with zero installation or build steps required.

1. Copy the HTML code and save it as `thermal_radiation_experiment.html` (or `index.html`).
2. Double-click the file to open it in any modern web browser (Chrome, Edge, Firefox, Safari).
3. Click **"بدء محاكاة الدقيقة 1"** (Start Minute 1 Simulation) to begin stepping through the experiment.

> **Note:** An active internet connection is required on load to fetch Tailwind CSS, Chart.js, and the Tajawal Arabic font from their respective CDNs.

## Technologies Used

* **HTML5** (RTL Arabic layout)
* **Tailwind CSS** (Styling and responsive grid layout)
* **Vanilla JavaScript** (`requestAnimationFrame` timer loop and DOM updates)
* **Chart.js** (Interactive line chart visualization)
