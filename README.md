# Rotational Animation

A visually appealing web-based rotational animation project built using **HTML**, **CSS**, and **JavaScript**. This animation simulates a rotating display effect with a seamless hover transition.

## Demo

![Rotational Animation Demo](images/demo.gif)

## Features

- Smooth rotational animation triggered by hover.
- Dynamic background transitions for enhanced visual appeal.
- Fully responsive design with modern CSS techniques.

## Getting Started

Follow these instructions to set up the project on your local machine.

### Prerequisites

- A web browser (e.g., Chrome, Firefox, Edge).
- A code editor (e.g., VS Code, Sublime Text).
- A local server for testing (optional, e.g., [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)).

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/rotational-animation.git
2. Navigate to the project directory:
   ```bash
   cd rotational-animation
3. Open the index.html file in your browser:
   ```bash 
   open index.html
  Or use a local server for better performance.

### Project Structure
    ```bash
    rotational-animation/
    ├── index.html       # Main HTML file
    ├── style.css        # CSS for styling and animations
    ├── images/          # Folder for images (backgrounds, mockups)
    │   ├── bg1.jpeg     # Background image 1
    │   ├── bg2.jpg      # Background image 2
    │   ├── mockup.png   # Mask image for the animation
    │   ├── demo.gif     # Optional: Demo gif for README
    └── README.md        # Project documentation 
    
### Usage

1. Hover over the animation container to trigger the rotation effect.
2. Adjust the background images in the style.css file for customization:
   ```css
   .pack {
      background: var(--bg), url(images/mockup.png);
   }

### Customization

1. Images: Replace bg1.jpeg, bg2.jpg, and mockup.png in the images folder with your own assets.
2. Animation Speed: Modify the transition property in style.css:
   ```css
    transition: 0.7s; /* Adjust speed */
3. Container Size: Change the width and height in the .cane class:
   ```css
    width: 500px;
    height: 500px;

### Technologies Used
1. HTML: For structuring the content.
2. CSS: For animations, styling, and responsiveness.
