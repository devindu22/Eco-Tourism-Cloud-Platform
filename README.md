# Eco-Tourism Cloud Platform (ETCP) 🌿🗺️

The **Eco-Tourism Cloud Platform (ETCP)** is a premium, highly interactive, single-file web application architecture designed for a visionary start-up in Sri Lanka. The platform aims to revolutionize how eco-conscious travelers discover, plan, and engage with sustainable travel experiences while providing local eco-tourism operators with advanced enterprise management tools.

This repository contains the complete frontend prototype, integrating contextual ecosystem themes, an interactive geographic SVG router, live localized state evaluation, and provider-side business intelligence analytics.

https://capable-kringle-b92860.netlify.app/

---

## 🚀 Core Architectural Features

### 1. Dynamic Ecosystem Themes

<img width="1911" height="916" alt="Screenshot 2026-07-06 215334" src="https://github.com/user-attachments/assets/e299eb27-4ef1-439d-9b9f-9f3af4d74278" />

The interface utilizes an active theme-switching runtime that rewrites primary UI tokens, structural glass-morphism values, color palettes, and ambient glow properties across three distinct environmental spaces:
* **Rainforest Canopy:** Deep emerald tones, jade accents, and organic forest styling.
* **Ocean Reef:** Marine blues, teal highlights, and deep sea depth gradients.
* **Mountain Mist:** Slate grays, misty charcoal, and crisp alpine highlights.

### 2. Eco-Discovery Hub

<img width="1911" height="916" alt="Screenshot 2026-07-06 215224" src="https://github.com/user-attachments/assets/e6153a83-6b6d-4dd1-96cd-0e0da8545046" />

An advanced catalog engine hosting rich, hand-crafted Sri Lankan eco-experiences (e.g., Sinharaja Rain Forest, Ella Rock, Yala Safari). 
* **Live Filtering:** Query filtering across location, activity types, and strict sustainability star metrics.
* **Transactional Engine:** Simulated dynamic booking calculations, interactive traveler review updates, and modular details presentation overlay modals.
* **Eco-Pass Integration:** Virtual membership wallet system featuring programmatic QR compilation and subscription status verification directly impacting checkout pricing workflows.

### 3. ETCP Voyager (Interactive SVG Routing)

<img width="1469" height="704" alt="Gemini_Generated_Image_us3dhnus3dhnus3d" src="https://github.com/user-attachments/assets/6332d259-2be3-4c5e-8250-5fb063c57bc5" />

A completely custom vector coordinate layout mapping Sri Lanka's critical logistical and ecotourism nodes (Mirissa, Ella, Sinharaja, Yala, Knuckles). 
* Calculates relative trip path matrices upon selection.
* Evaluates carbon footprint and sustainability index metrics dynamically against chose transport variables (Train, Hybrid, EV).

### 4. Eco-Journeys Dashboard

<img width="1913" height="918" alt="Screenshot 2026-07-06 215244" src="https://github.com/user-attachments/assets/0a6bf286-98f8-4c22-a4c8-3b4cd9df79d1" />

A personalized command center tracking individual itinerary actions:
* **Carbon Offset Tracker:** Visual metrics displaying saved $CO_2$ volumes and total sustainability points accrued.
* **State-driven Wishlist:** Localized state container managing user-saved items.
* **Recommendation Engine:** Contextual predictive system recommending sibling properties based on current interaction models.

### 5. Eco-Explorer Network (EEN)

<img width="1913" height="918" alt="Screenshot 2026-07-06 215321" src="https://github.com/user-attachments/assets/4375f349-986e-4d3f-8bf8-2930eeba1a32" />

An administrative portal tailored for native eco-hosts, providers, and conservation projects.
* **Business Intelligence Reporting:** Chart.js canvas render engines outputting real-time revenue analytics and visitor acquisition demographics.
* **Dynamic Catalog Publisher:** Form parser that programmatically injects freshly submitted properties into the main consumer catalog arrays without necessitating hard reloads.

### 6. Accessibility Suite
Built to adhere to modern WCAG criteria, featuring an immediate UI font-scaling pipeline and a strict high-contrast mode toggle to preserve accessibility parameters across low-visibility environments.

---

## 🛠️ Technology Stack

| Layer | Technology | Distribution Method |
| :--- | :--- | :--- |
| **Structure** | HTML5 (Semantic Layouts) | Native |
| **Styling** | Tailwind CSS | JIT Utility Engine via CDN |
| **Icons** | FontAwesome v6 | Vector Library via CDN |
| **Charts** | Chart.js | Canvas Analytics Engine via CDN |
| **Logic Engine** | Vanilla JavaScript (ES6+) | Native State & Event Routing |

---

## ⚡ Quick Start & Deployment

### Local Execution

Because the platform relies entirely on browser-native execution and standard CDNs, no local package installation (npm install) is required.

1. Clone or download the repository files.

2. Launch the application directly:

Option A: Double-click index.html to run inside your default web browser via the file system protocol.

Option B: Serve via a local utility runner like VS Code's Live Server extension to establish an internal http://localhost environment.

### Hosting Configuration

To upload this platform to free or shared hosting environments (such as InfinityFree via FTP):

1. Connect using an FTP client (e.g., FileZilla).

2. Transfer index.html directly into your designated public root directory (typically /htdocs or /public_html).

3. Ensure an active internet connection is maintained on the client browser to pull required CSS assets and runtime graphing frameworks smoothly.

## 🔧 Core State Engine Specification

The system manages runtime components through a centralized JavaScript tracking literal:

JavaScript
// System Application State Architecture Reference

let appState = {

    currentTheme: 'rainforest',
    fontSizeClass: 'text-base',
    highContrast: false,
    wishlist: [],
    catalog: [/* 10 Predetermined Eco-Properties */],
    bookings: [],
    voyagerRoute: { start: null, end: null, transit: 'train' },
    ecoPass: { active: false, tier: null }
    
};

All interactions trigger an immediate application state updates sequence, automatically followed by programmatic DOM UI view mutations to guarantee view-layer synchronicity.

---

## 📂 File Structure

The application is structured as a Single File Architecture. Styles, structural layouts, and state manipulation logic are contained inside a cohesive index.html file to facilitate rapid testing, serverless platform deployment (e.g., InfinityFree, Netlify), and zero-overhead performance prototyping.

```static
├── index.html       # Unified single-file layout containing markup, styles, and state scripts
└── README.md        # Technical project documentation
