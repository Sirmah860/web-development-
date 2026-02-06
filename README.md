# Cosmic Explorer Dashboard 🚀

Interactive Space Exploration Dashboard built with React and NASA APIs - A comprehensive web application for exploring space data including daily astronomy images, Mars rover photos, and near-Earth objects tracking.

![Cosmic Explorer](https://img.shields.io/badge/React-19.2-blue)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-3.4-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## 🌟 Features

### 📸 Astronomy Picture of the Day (APOD)
- Browse NASA's daily space images and videos
- Select any date to view historical astronomy pictures
- Read detailed explanations and copyright information
- Save your favorite APODs for quick access

### 🔴 Mars Rover Gallery
- View authentic photos from Mars rovers (Curiosity, Opportunity, Spirit)
- Filter by Martian sol (day)
- See detailed camera and mission information

### ☄️ Near Earth Objects (NEO) Tracker
- Track asteroids approaching Earth in real-time
- Interactive charts showing size and velocity comparisons
- Filter by name and hazard status
- View detailed approach data

### ⭐ Additional Features
- **Favorites System**: Save items across all tabs
- **Dark/Light Mode**: Toggle between themes
- **Responsive Design**: Mobile, tablet, and desktop support
- **Accessible**: WCAG 2.1 AA compliant
- **Interactive Charts**: Data visualization using Recharts

## 🚀 Quick Start

### Installation & Setup

1. **Get your NASA API key** (free at [https://api.nasa.gov/](https://api.nasa.gov/))

2. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env and add your NASA API key
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open [http://localhost:3000](http://localhost:3000)**

## ⚠️ Important API Notes

### NASA API Status Updates
- **Mars Rover Photos API**: Currently archived by NASA but still functional. All historical Mars rover images remain accessible.
- **Earth API**: Has been replaced with Earthdata GIBS API (not implemented in this project)
- **APOD & NEO APIs**: Fully active and supported

This project uses the archived Mars Rover API for educational purposes. The data remains available and functional for learning and demonstration.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
