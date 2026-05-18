# RouteWatch

RouteWatch is a modern web application built with React, Vite, and TailwindCSS. It integrates mapping features, weather data, and AI-powered insights to provide a comprehensive route tracking and monitoring experience.

## Features

- **Interactive Maps**: Built using `react-simple-maps` and `d3-geo` for data visualization on interactive maps.
- **Real-time Weather**: Integration with OpenWeather API to display relevant weather data.
- **AI Insights**: Uses Google's Gemini API for intelligent features.
- **Backend as a Service**: Powered by Firebase for authentication, database (Firestore), and storage.
- **Modern UI**: Styled with TailwindCSS for a responsive and modern user interface.

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sahil-k-Sahoo/routewatch.git
   cd routewatch
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Environment Setup:
   Copy the `.env.example` file to create a new `.env` file:
   ```bash
   cp .env.example .env
   ```
   Fill in the required API keys and configuration values in the `.env` file:
   - Firebase config keys
   - OpenWeather API key
   - Gemini API key

### Running the App

Start the development server:
```bash
npm run dev
```

### Building for Production

Build the app for production:
```bash
npm run build
```

## Technologies Used

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- [Firebase](https://firebase.google.com/)
- [React Simple Maps](https://www.react-simple-maps.io/)
- [React Router DOM](https://reactrouter.com/)
