# NaviSafe: AI-Powered Safety Navigation

NaviSafe is a modern navigation application that prioritizes driver safety by integrating real-time routing with historical accident data and artificial intelligence.

## Features

- **Safety-First Routing**: Visualizes "black spots" (accident-prone areas) on the map and identifies risks along your planned path.
- **AI Safety Briefings**: Generates conversational briefings using Google Gemini (via Genkit) to warn drivers about specific hazards.
- **Real-time Navigation**: Turn-by-turn mode with dynamic speed, ETA, and remaining distance tracking.
- **Proximity Alerts**: Visual and audible warnings when approaching high-risk zones.
- **Crowdsourced Safety**: Allows users to report new black spots or confirm existing ones to improve community safety.
- **Multi-Modal Support**: Optimized routing for both cars and bicycles.

## Tech Stack

- **Frontend**: Next.js 15 (App Router), React, Tailwind CSS, ShadCN UI.
- **Mapping**: Leaflet.js with OpenStreetMap and OSRM (Open Source Routing Machine).
- **Backend & Auth**: Firebase Firestore and Firebase Authentication.
- **AI Engine**: Genkit with Google Gemini 2.5 Flash.

## Getting Started

1.  **Environment Setup**: Ensure your `.env` file contains the necessary `GEMINI_API_KEY`.
2.  **Install Dependencies**: `npm install`
3.  **Run Development Server**: `npm run dev`
4.  **Access the App**: Open [http://localhost:9002](http://localhost:9002) in your browser.

## Project Structure

- `src/components/`: React UI components.
- `src/app/`: Next.js page routes and layouts.
- `src/ai/`: Genkit AI flows and configuration.
- `src/firebase/`: Firebase client initialization and custom hooks.
- `docs/`: Detailed project documentation and backend schema.

---
*Powered By Group 2 S6C*
