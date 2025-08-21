# Strength Training Sessions App

A simple web app to log and review your strength training sessions. Sessions are organized by week and session type (e.g., Upper 1, Lower 1). Each session contains exercises and sets, and all data is stored in your browser's localStorage.

## Features
- Add new training weeks and select session templates (Upper 1, Lower 1, Upper 2, Lower 2)
- Enter sets, reps, and weight for each exercise
- View all saved sessions in a clean, responsive table layout
- Data is saved locally in your browser (no backend required)

## Usage
1. Open `index.html` in your browser.
2. Enter a week and select a session to start logging.
3. Fill in the sets, reps, and weight for each exercise.
4. Save the session. All sessions are displayed in tables below the form.

## Development
- All logic and UI are in `index.html`.
- Session structure examples are in `example.json`.
- To clear all data, open the browser console and run:
  ```js
  localStorage.removeItem('trainingSessions');
  ```

## License
MIT

