# Focus Tracker Web App

This is a simple web app for tracking focus sessions with an integrated digital clock, timer, and break settings. The app is built using HTML, CSS, and JavaScript with Bootstrap for styling.

## Features

- **Digital Clock**: Displays the current time based on the user's timezone.
- **Configurable Timer**: Allows the user to set a focus session duration from 5 to 120 minutes.
- **Break Timer**: Optional break intervals of up to 5 minutes between focus sessions.
- **Session Statistics**: Stores and displays the last 5 days of session data, saved in the browser's local storage.
- **Responsive Design**: Uses Bootstrap for a clean, modern look and responsive design.

## Requirements

- A modern web browser (Chrome, Firefox, Edge, Safari) with JavaScript enabled.

## Installation

1. **Clone the Repository** (if applicable) or download the code.
2. Open the HTML file (`index.html`) directly in a web browser to start using the app.

## Usage

1. **Set Timer**: Adjust the session duration (5-120 minutes) and break duration (optional) from the inputs provided.
2. **Start**: Click the **Start** button to begin the session. The timer will count down the time remaining.
3. **Pause**: Click the **Pause** button to temporarily stop the timer. Clicking it again will resume the timer.
4. **Reset**: Click **Reset** to stop the session and reset the timer display.
5. **Statistics**: The app automatically logs each session duration and displays data from the last 5 days in the sidebar.

## Code Structure

- **HTML**: Sets up the app's layout, including the digital clock, timer display, and controls.
- **CSS**: Basic styles are included to enhance the layout and visuals, along with Bootstrap for additional styling.
- **JavaScript**: Handles the timer functionality, session control, and browser storage for session data.

## Customization

- You can adjust the timer and break durations in the HTML inputs.
- Modify CSS styles or use another CSS framework if desired.

## Browser Support

- **Local Storage**: The app uses `localStorage` to store session data, which is supported by all modern browsers.
- **JavaScript**: Ensure JavaScript is enabled in your browser.

## License

This project is free to use under the MIT License.
