# Habit App

A simple and beautiful habit tracking application built with vanilla JavaScript.

## Demo

Live demo: [https://vitalychernov.github.io/habbit_app/](https://vitalychernov.github.io/habbit_app/)

## Features

- Create and track multiple habits
- Set target goals for each habit (number of days)
- Track daily progress with comments
- Visual progress bar showing completion percentage
- Choose from different habit icons (sport, water, food)
- Data persistence using localStorage
- Direct link sharing via URL hash

## Screenshots

The app includes:
- Left sidebar with habit icons for quick navigation
- Progress bar showing how close you are to your goal
- Daily log with comments and delete functionality
- Popup form for adding new habits

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- LocalStorage for data persistence

## Getting Started

### Prerequisites

No prerequisites required - this is a static web application.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/vitalychernov/habbit_app.git
```

2. Open `index.html` in your browser, or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

3. Navigate to `http://localhost:8000`

## Usage

1. **Add a new habit**: Click the "+" button in the sidebar
2. **Select an icon**: Choose sport, water, or food icon
3. **Set your goal**: Enter the habit name and target days
4. **Track daily progress**: Add a comment for each day you complete
5. **Monitor progress**: Watch your progress bar fill up as you reach your goal

## Project Structure

```
habbit_app/
├── index.html          # Main HTML file
├── styles/
│   └── main.css        # Styles
├── scripts/
│   └── app.js          # Application logic
├── images/             # Icons and images
│   ├── logo.svg
│   ├── sport.svg
│   ├── water.svg
│   ├── food.svg
│   └── ...
└── README.md
```

## License

This project is open source and available under the [MIT License](LICENSE).
