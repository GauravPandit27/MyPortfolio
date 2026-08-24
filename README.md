# Gaurav Pandit — Digital Mandir Portfolio

This repository contains the source code for Gaurav Pandit's interactive 3D portfolio, featuring an integrated AI Chatbot powered by NVIDIA Nemotron.

## Features
- **3D Universe Animation**: Built with Three.js.
- **Digital Guru Chatbot**: Connects to NVIDIA NIM API with 2 modes ("About Me" and "About Projects").
- **Custom Proxy Server**: A Flask backend to handle API calls securely and bypass CORS restrictions.
- **Responsive Design**: Works on desktop and mobile.

## How to Run Locally

Since this project now uses a custom Python backend proxy to securely handle the NVIDIA API key for the chatbot, you must run it using the provided Python server instead of just double-clicking `index.html`.

### Prerequisites
1. **Python 3.8+** must be installed.
2. Install the required Python packages:
   ```bash
   pip install flask flask-cors requests
   ```

### Running the Server
1. Open a terminal/command prompt in this `MyPortfolio` directory.
2. Run the proxy server:
   ```bash
   python server.py
   ```
3. Open your web browser and navigate to:
   **http://localhost:5000**

### Using the Chatbot
Scroll to the bottom "Contact" section to find the **Digital Guru** chatbot.
- Select **About Me** to ask about Gaurav's background, education, and philosophy.
- Select **About Projects** to ask detailed technical questions about his AI projects.
