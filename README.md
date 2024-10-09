# Interactive Eye Movement

This project creates a fun and interactive web page where two "eyes" follow the user's mouse movements. The pupils (represented as small balls) move based on the position of the mouse pointer, simulating eye movement in real-time.

## Features

- **Dynamic Mouse Tracking**: The pupils follow the mouse cursor as it moves around the screen.
- **Smooth Animation**: The pupils smoothly adjust their position, giving the illusion of natural eye movement.
- **Responsive Design**: The size and movement of the pupils adapt to the window size, making it work well across different devices.

## How It Works

### HTML Structure

The HTML consists of two main elements for the eyes:

1. **Eye Divs**: Each eye is represented by a `div` with the class `eye`.
2. **Pupils (Balls)**: Inside each `eye`, there is a smaller `div` with the class `ball`, which represents the pupil.

```html
<div class="eye">
    <div class="ball"></div>
</div>
