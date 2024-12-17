# Flask Meme Website

A simple web application built with Flask that fetches and displays random memes from the [Meme API](https://meme-api.com/gimme).
<br/>
The page refreshes automatically every 30 seconds to showcase a new meme.

## Features

- Fetches random memes using the Meme API.
- Displays the meme along with its source subreddit.
- Auto-refreshes every 30 seconds for fresh content.
- Simple and clean UI with a responsive design.

## Installation

Follow these steps to set up and run the project:

### 1. Clone the repository
   ```bash
   git clone https://github.com/antonrezin/FlaskMemeWebsite
   cd FlaskMemeWebsite
   ```

### 2. Set up a virtual environment
   - On Windows:
     ```bash
     py -3 -m venv .venv
     ```
   - On macOS/Linux:
     ```bash
     python3 -m venv .venv
     ```

### 3. Activate the virtual environment
   - On Windows:
     ```bash
     .venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     . .venv/bin/activate
     ```

### 4. Install required dependencies
   ```bash
   pip install flask requests
   ```

### 5. Run the application
   ```bash
   python meme_flask.py
   ```

### 6. Open the app in your browser
   ```
   http://localhost:5000 or http://127.0.0.1:5000
