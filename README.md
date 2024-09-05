# Editorium-PWA
Just Another Text Editor - Progressive Web App
Here’s a README file tailored for your text editor project, following the format you provided:

---

# J.A.T.E. (Just Another Text Editor)

## Description
J.A.T.E. is a Progressive Web Application (PWA) that functions as a text editor within the browser. It supports offline functionality and uses IndexedDB for data persistence. The application allows users to create and save notes or code snippets even without an internet connection.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/AshleydVon/Editorium-PWA
   cd Editorium-PWA
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   - Create a `.env` file in the root directory with the following content:
     ```plaintext
     MONGODB_URI=mongodb+srv://ashleydvon:aZ16gZdAwTJKiEIw@cluster0.sqtgf.mongodb.net/mydatabase?retryWrites=true&w=majority
     PORT=8080
     NODE_ENV=production
     ```

4. **Build the project:**
   ```bash
   npm run build
   ```

## Usage
1. **Start the server:**
   ```bash
   npm start
   ```

2. **Open your browser and navigate to:**
   ```
   http://localhost:8080
   ```

3. **Use the text editor to create and save notes or code snippets.**

## Features
- **Offline Functionality**: Allows users to create and save notes even when offline.
- **Data Persistence**: Uses IndexedDB to store and retrieve data.
- **Progressive Web Application (PWA)**: Can be installed on your desktop as an icon.
- **Service Worker**: Registers a service worker to cache static assets and pages for offline use.
- **Bundled with Webpack**: JavaScript files are bundled and optimized for production.

## Technologies Used
- **Node.js**: Server-side JavaScript runtime environment.
- **Express.js**: Web framework for Node.js.
- **IndexedDB**: Browser database for storing data.
- **idb**: Lightweight IndexedDB wrapper.
- **Webpack**: Module bundler for JavaScript applications.
- **WebpackPwaManifest**: Generates a manifest file for PWA.
- **Workbox**: Creates a service worker to handle caching and offline functionality.
- **dotenv**: Manages environment variables.

## Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## Deployed Render Webservice
(https://editorium-pwa-10.onrender.com
)
## License
This project is licensed under the ISC License.

---

Feel free to adjust any details, such as the GitHub URL, to match your actual repository information.
