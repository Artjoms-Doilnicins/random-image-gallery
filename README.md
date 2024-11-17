# Random Image Generator

[https://artjoms-doilnicins.github.io/random-image-gallery/](https://artjoms-doilnicins.github.io/random-image-gallery/)

A simple web app that displays random images and allows the user to load more images by clicking a button. The app uses the Picsum API to fetch random images and displays them in a grid format. Images are styled to zoom in when hovered over, adding interactivity.

## Features

### HTML

The interface includes:
- **Images**: Six random images from the Picsum API are displayed initially.
- **Button**: A button that, when clicked, loads more images and appends them to the image grid.
  
### CSS

- **Design**:
  - The page has a light gradient background, making the images stand out visually.
  - The images are styled to have rounded corners and a subtle shadow effect to give them a clean, modern look.
  - The button has a unique hover and active effect, with a conic gradient background that animates on interaction.

- **Responsive Layout**:
  - The images are displayed in a flexible grid that adapts to screen size, ensuring the interface is responsive.

### JavaScript

- **Initial Image Load**:
  - When the page loads, six random images are fetched from the Picsum API and displayed in the `.img-container` div.
 
- **Button Functionality** : 
  - When the "Click here to load more images" button is clicked, the `addNewImages()` function is called.
 
  - The function creates a new `img` element, sets a random image source from the Picsum API, and appends it to the container.
 
- **Image Hover Effect** : 
  - The images have a zoom effect applied when hovered over. This is achieved with the `transform: scale(1.1)` CSS property and transition timing.


## How It Works

1. Click the "Click here to load more images" button to load additional random images.
