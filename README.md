# Flask Starter Web App

This is a minimal Flask web application starter, ready for local development and deployment to Render.

## Local Setup

1. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
2. Activate the virtual environment:
   - On Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - On Mac/Linux:
     ```bash
     source venv/bin/activate
     ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the app:
   ```bash
   python app.py
   ```

## Deploy to Render

1. Push your code to a Git repository (GitHub, GitLab, etc.).
2. Create a new Web Service on Render, connecting your repo.
3. Set the build and start commands:
   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `python app.py`

Or use the included `render.yaml` for one-click deploy.
