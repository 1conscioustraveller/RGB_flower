README.md
markdown
# RGB Geometric Flower

An animated geometric flower pattern rendered using HTML5 Canvas with RGB color transitions.

![RGB Geometric Flower Demo](demo.gif) *(Replace with actual screenshot or gif)*

## Features

- Configurable number of petals
- Adjustable animation speed
- Smooth RGB color transitions based on position
- Responsive design that works on different screen sizes
- Clean, trail-based animation effect

## Customization

You can easily modify the following parameters in the JavaScript code:

```javascript
const PETALS = 12;         // Change number of petals
const DOTS_PER_PET = 90;   // Change number of dots per petal
const DOT_RADIUS = 2;      // Adjust dot size
const PETAL_WIDTH = 0.45;  // Adjust petal width (0-1)
const SPEED = 0.6;         // Change animation speed
How It Works
The animation creates a flower pattern by:

Positioning dots along each petal

Calculating RGB values based on the dot's position and current angle

Animating the dots in a circular motion

Using requestAnimationFrame for smooth rendering

Installation
No installation required! Just open the HTML file in any modern browser.

Technologies Used
HTML5 Canvas

Vanilla JavaScript

CSS for basic styling
