# Stopwatch Timer Application

A clean, responsive stopwatch application built with vanilla JavaScript, HTML, and CSS. The application features a sleek design with a pulsing timer display and lap recording functionality.



## Features

- **Precise Timing**: Measures time with millisecond precision
- **Intuitive Controls**: Start, stop, pause, and reset functionality
- **Lap Recording**: Save and display lap times
- **Responsive Design**: Works on mobile and desktop devices
- **Animated UI**: Subtle animations enhance the user experience

## Demo

Check out the live demo [here](https://ParthSharma30.github.io/stopwatch-timer/)

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/ParthSharma30/stopwatch-timer.git
cd stopwatch-timer
```

No additional dependencies are required. Simply open `index.html` in your web browser to run the application.

## Usage

1. Click the **Start** button to begin the timer
2. Click **Pause** to temporarily halt the timer
3. Click **Stop** to halt the timer and record a lap time
4. Click **Reset** to clear the current timer without recording a lap
5. Lap times are displayed in the "Lap Timer" section below the controls

## Project Structure

```
stopwatch-timer/
├── index.html      # Main HTML structure
├── style.css       # Styling and animations
└── script.js       # Timer functionality
```

## Code Overview

### HTML Structure

The application uses a simple HTML structure with:
- Timer display showing minutes, seconds, and milliseconds
- Control buttons (Start, Stop, Pause, Reset)
- Lap time recording section

### CSS Styling

The styling includes:
- Gradient background
- Card-based layout with shadows
- Animated timer display with a pulsing effect
- Responsive design that works on various screen sizes

### JavaScript Functionality

The JavaScript handles:
- Timer logic using `setInterval`
- Button event listeners
- Lap time recording
- Time formatting with padded zeros

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by classic stopwatch applications
- Built as a learning project for JavaScript timing functions
