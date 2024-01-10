# Gallery Plugin

Transform your image collections into stunning galleries effortlessly with this jQuery plugin! Developed as part of my jQuery course at Information Technology Institute (ITI). Excited to share this project—hope you find it as impressive as I do! 🚀


![Your Image Alt Text](https://drive.google.com/uc?export=view&id=1SczNMpWETKq6r5Yz-CETEnYrElpci7W9)


## Demo

View the live demo [here](https://mo3lii.github.io/Gallery-Project/).

## Features

- Grid layout for images
- Full view mode
- Smooth image sliding

## How To Use : 

1. **Include jQuery:**

   Ensure you have jQuery included in your project. You can download it or use a CDN.

    ```html
    <script src="./gallery-plugin/jquery.js"></script>
    ```
      or use CDN
   ```html
      <script src="https://code.jquery.com/jquery-3.7.1.js" integrity="sha256-eKhayi8LEQwp4NKxN+CfCh+3qOVUtJn3QNZ0TciWLP4=" crossorigin="anonymous"></script>
   ```

2. **Include `gallery-plugin.js` file:**

   Include the `gallery-plugin.js` file in your HTML.

    ```html
    <script src="./gallery-plugin/gallery-plugin.js"></script>
    ```

4. **Include `gallery-plugin.css` style file:**

   Include the `gallery-plugin.css` file for styling your gallery.

    ```html
    <link rel="stylesheet" href="./gallery-plugin/gallery-plugin.css" />
    ```

5. **Include Font Awesome or use CDN:**

   Include Font Awesome for icons or use the CDN.

    ```html
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"/>
    ```

6. **Set up your HTML structure:**

   Create a container for your images with a class, for example, `your-image-collection`.

    ```html
    <div class="your-image-collection">
      <!-- Your image elements go here -->
      <img src="path/to/image1.jpg" alt="Image 1">
      <img src="path/to/image2.jpg" alt="Image 2">
      <!-- Add more images as needed -->
    </div>
    ```

7. **Initialize the gallery plugin:**

   Call the `.galleryPlugin()` function on your image collection container.

    ```javascript
    $('.your-image-collection').galleryPlugin();
    ```

🚀 Developed by [Mostafa Ali](https://www.linkedin.com/in/mostafa-ali-462152203/) - Check out my LinkedIn profile for more projects and updates!
