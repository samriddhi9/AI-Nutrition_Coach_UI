# React + TypeScript + Vite

# Calorie Counter

A React web app that estimates the calories in a meal from a photo. Upload an image or take one with your camera, and the app is designed to analyze it with an LLM and return a calorie estimate.

> **Status:** Work in progress. The UI is still being developed, and the AI analysis depends on a backend that is also being built.

## About This Project
This is a learning project built by Samriddhi Bhosle and her husband, Modassir, to practice new technologies together. Samriddhi builds the React frontend, and Modassir builds the Java backend. The repository is a fork so that both of us can contribute.

As spouses, we work on one shared laptop, so some frontend commits may appear under Modassir's name. All frontend code (UI, camera and upload flow, LLM integration) is written by Samriddhi.

## Features
- Upload a meal image or capture one using the device camera
- React-based UI (in progress)
- LLM integration for calorie estimation (works in local development only, see note below)

## Important Note on the Live Demo
The live demo on GitHub Pages shows the **UI only**, and it is still in progress. The AI analysis does not work there because it needs an API key, and API keys must never be exposed in a frontend app. The correct approach is to call the LLM through a backend that keeps the key private. That Java backend is currently in progress.

## Tech Stack
- React
- JavaScript
- HTML5, CSS3
- LLM API (integration in progress)
- Java backend (in progress)

## Getting Started
1. Clone this repository and open the project folder
2. Install dependencies
   ```bash
   npm install
   ```
3. Start the app
   ```bash
   npm start
   ```
The app runs at `http://localhost:3000`.

## Roadmap
- Complete the UI
- Secure backend integration so AI analysis works in the deployed app
- Meal history
- Daily calorie goals

## Contributors
- **Samriddhi Bhosle**: React frontend, UI, LLM integration
- **Modassir** (spouse): Java backend

## Author
Samriddhi Bhosle
