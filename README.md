# Digital Clock

A beautiful, modern digital clock web application built with HTML, CSS, and JavaScript. Displays the current time in hours, minutes, and seconds with a sleek, glassmorphic design.

## Preview

![Digital Clock Preview](src/Screenshot%202026-01-28%20121359.png)

The clock shows the current time in a visually appealing interface with a gradient background and glassmorphic effect.

## Features

- ⏰ **Real-time Display** - Updates every second to show the current time
- 🎨 **Modern Design** - Glassmorphic UI with gradient background
- 📱 **Responsive** - Works on various screen sizes
- 🟢 **Vibrant Colors** - Green and gradient color scheme with decorative elements
- 🔄 **Auto-updating** - Automatically displays the current system time

## Project Structure
Create-a-Digital-clock/
├── index.html # Main HTML file with clock markup and JavaScript
├── style.css # CSS styling for the clock interface
├── README.md # Project documentation
└── src/ # Assets directory
└── Screenshot 2026-01-28 121359.png


## Technologies Used

- **HTML5** - Markup structure
- **CSS3** - Styling with gradients, backdrop-filters, and pseudo-elements
- **JavaScript** - Real-time clock functionality using the Date API

## How It Works

The clock uses JavaScript's `setInterval()` function to:
1. Get the current time using `new Date()`
2. Extract hours, minutes, and seconds
3. Format the time with leading zeros (e.g., 01, 02, etc.)
4. Update the display every 1000 milliseconds (1 second)

## Created by

Nilakshi Sandeepani Bandara



