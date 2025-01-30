# Glassmorphism

Glassmorphism is a modern UI design trend that gives the illusion of frosted glass elements within a user interface. This project demonstrates how to implement Glassmorphism effects using HTML, CSS, and JavaScript.

## Features

- Stylish frosted glass effect using CSS `backdrop-filter`.
- Responsive design, ensuring it works well across different screen sizes.
- Interactive and aesthetically pleasing design.
- Easy-to-integrate HTML/CSS code that can be used in any web project.

## Installation

To use the Glassmorphism effect in your own projects, follow these steps:

1. Clone this repository:

    ```bash
    git clone https://github.com/edilsonolegario/Glassmorphism-
    ```

2. Open the `index.html` file in your browser to see the effect in action.

3. Customize the design by modifying the CSS styles in `style.css`.

## Usage

You can add the Glassmorphism effect to any section of your webpage by applying the provided CSS classes. Just include the necessary styles and HTML structure from the project, and you're good to go!

### Example Usage:

```
HTML
<div class="glass-container">
  <h1>Glassmorphism Effect</h1>
  <p>Welcome to the world of frosted glass design!</p>
</div>

CSS
.glass-container {
  background: rgba(255, 255, 255, 0.1);
  border-radius: 15px;
  backdrop-filter: blur(10px);
  padding: 20px;
  text-align: center;
}
