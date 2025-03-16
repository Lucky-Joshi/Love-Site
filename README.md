# Love Animation 💗 | Gamma Bytes

This project is a beautiful love animation created using HTML5 Canvas and JavaScript. The animation features a heart shape that pulses and glows, along with a lovely message that appears on the screen.

## Features

- Heart shape animation with pulsing and glowing effects.
- Lovely message "I love you" displayed with a jumping and color-changing effect.
- Responsive design that adjusts the animation for different screen sizes.
- Attribution to the original creator.

## Technologies Used

- HTML5
- CSS3
- JavaScript

## Code Explanation

### HTML (`index.html`)

The HTML file sets up the structure of the webpage. It includes:

- A `canvas` element for the heart animation.
- A `div` element with the id `love-message` for displaying the love message.
- Meta tags for character encoding, viewport settings, and compatibility.
- A link to a Google font used in the love message.
- Inline CSS for styling the canvas, love message, and other elements.

### CSS (`index.html`)

The CSS styles the canvas and the love message. It includes:

- Styles for the `canvas` element to position it and set its background color.
- Styles for the `#love-message` element to position it, set its font properties, and apply animations.
- Keyframe animations (`jump` and `colorChange`) for the love message to create jumping and color-changing effects.
- Media queries to adjust the styles for different screen sizes.

### JavaScript (`index.html`)

The JavaScript code handles the animation logic. It includes functions to:

- Initialize the canvas and set its size based on the device type (mobile or desktop).
- Draw the heart shape and animate it with pulsing and glowing effects.
- Create and animate glowing hearts that float upwards.
- Display the "I love you" message after a certain number of hearts have passed.

Key parts of the JavaScript code:

- `requestAnimationFrame` is used to create a smooth animation loop.
- Event listeners are added to handle window resizing and document loading.
- The `heartPosition` function calculates the coordinates of points on the heart shape.
- The `pulse` function updates the target points for the heart animation.
- The `loop` function is the main animation loop that updates the canvas and draws the hearts and love message.

## How to Run

1. Clone or download the repository to your local machine.
2. Open the `index.html` file in your preferred web browser.
3. Enjoy the love animation!

## Attribution

Original creator: [Gamma Bytes](https://www.instagram.com/gammabytesofficial?utm_source=ig_web_button_share_sheet&igshid=ZDNlZDc0MzIxNw==)

## License

This project is licensed under the MIT License.
