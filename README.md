# Hover Text Animation

This project features a hover text animation effect that simulates a "hacker" or "glitch" effect when the mouse hovers over a specified text. The text changes randomly before resolving to a predefined value.

<img width="1221" alt="Screenshot 2024-08-31 at 11 09 39 PM" src="https://github.com/user-attachments/assets/6fa63164-8170-41f3-b9c0-0e1dc88f9832">


## Features

- **Random Letter Glitch Effect**: The text in the `<h1>` element randomly changes letters when hovered over, simulating a glitchy or hacker-like effect.
- **Smooth Transition**: The text gradually transitions from random characters to the correct characters, creating a visually appealing effect.
- **Responsive Design**: The animation works seamlessly across different screen sizes.

## Technologies Used

- **HTML5**: The basic structure of the page.
- **CSS3**: Styling of the page, including font choice and layout.
- **JavaScript (ES6)**: Handles the hover effect and text transformation.

## How It Works

1. **HTML**: The `<h1>` element contains a `data-value` attribute that holds the final text that will appear after the animation completes.

2. **CSS**: The page is styled with a black background, white text, and a monospace font to enhance the glitch effect.

3. **JavaScript**: 
   - An event listener is added to the `<h1>` element to trigger the text transformation on mouseover.
   - The text randomly changes letters using characters from the English alphabet (`A-Z`).
   - The correct letters are progressively revealed based on the original text provided in the `data-value` attribute.


## Customization

- **Change the Text**: Modify the `data-value` attribute in the `<h1>` tag to change the final text.
- **Adjust Animation Speed**: Modify the `setInterval` delay (currently set to 30ms) in `scripts.js` to speed up or slow down the animation.