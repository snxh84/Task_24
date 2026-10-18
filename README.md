# Hello World - ReactJS

A basic "Hello World" React application that displays **Hello, World!** on the screen.

## Problem Statement

Develop a basic "Hello World" React application that displays the text "Hello, World!" in the browser.

## Tech Stack

- **React** (v18) – UI library
- **Vite** – build tool and dev server

## Project Structure

```
hello-world-react/
├── index.html          # Entry HTML file
├── package.json        # Dependencies and scripts
├── vite.config.js      # Vite configuration
└── src/
    ├── main.jsx        # React entry point, renders App into #root
    ├── App.jsx         # App component that displays "Hello, World!"
    ├── App.css         # Styles for the App component
    └── index.css       # Global styles
```

## How It Works

1. `index.html` contains a `<div id="root">` and loads `/src/main.jsx`.
2. `main.jsx` uses `ReactDOM.createRoot` to mount the `<App />` component into the root div.
3. `App.jsx` is a functional component that renders the heading **Hello, World!**.

## How to Run Locally

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the development server:
   ```bash
   npm run dev
   ```
3. Open the URL shown in the terminal (usually `http://localhost:5173`) in your browser.

You will see **Hello, World!** displayed on the screen.

## Build for Production

```bash
npm run build
```

This generates an optimized production build in the `dist` folder. Preview it with:

```bash
npm run preview
```
