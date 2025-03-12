# Micro-Mentor Frontend

A React and Tailwind CSS application for the Micro-Mentor AI platform - a personalized advice service that helps users tackle various challenges.

## Features

- Clean, responsive UI built with Tailwind CSS
- Challenge input and advice display
- API communication with Micro-Mentor AI backend
- Loading states and error handling

## Getting Started

### Prerequisites

- Node.js 14.x or higher
- npm 6.x or higher

### Installation

1. Clone the repository
   ```
   git clone https://github.com/Peak-new/micro-mentor-frontend.git
   cd micro-mentor-frontend
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Start the development server
   ```
   npm start
   ```

## Project Structure

```
├── public/
├── src/
│   ├── components/     # Reusable UI components
│   ├── pages/          # Page components
│   ├── services/       # API services
│   ├── utils/          # Helper functions
│   ├── App.js          # Main application component
│   └── index.js        # Entry point
├── .gitignore
├── package.json
├── postcss.config.js
└── tailwind.config.js
```

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production

## Tech Stack

- React 18
- Tailwind CSS
- PostCSS