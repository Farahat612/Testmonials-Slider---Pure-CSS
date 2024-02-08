# Slider Component

A simple HTML/CSS slider component for showcasing content in a visually appealing manner.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Usage](#usage)
- [Customization](#customization)
- [License](#license)

## Demo

> Explore the short video demo of this component:

<div align="center">
    

https://github.com/Farahat612/Testmonials-Slider---Pure-CSS/assets/67427124/4cbfb070-784f-4f57-be21-81285e2f925c


</div>

> Or, you can explore the live demo of this component [here](#).

## Features

- Smooth transitions between slides
- Easy to integrate into existing projects
- Customizable navigation buttons

## Usage

To use this slider component in your project, follow these steps:

1. Clone or download this repository.
2. Include the `style.css` file in the `<head>` section of your HTML file:

   ```html
   <link rel="stylesheet" href="path/to/style.css" />
   ```

3. Copy the HTML structure of the slider component into your HTML file:

   ```html
   <!-- Slider Parent -->
   <div class="slider">
     <!-- Navigation Buttons -->
     <input
       type="radio"
       name="slider"
       title="slider1"
       checked="checked"
       class="nav"
     />
     <input type="radio" name="slider" title="slider2" class="nav" />
     <input type="radio" name="slider" title="slider3" class="nav" />
     <input type="radio" name="slider" title="slider4" class="nav" />

     <!-- Inner Content parent -->
     <div class="inner">
       <!-- Slide 01 -->
       <div class="contents">
         <!-- Slide content goes here -->
       </div>
       <!-- End Of Slide 01 -->

       <!-- Slide 02 -->
       <div class="contents">
         <!-- Slide content goes here -->
       </div>
       <!-- End Of Slide 02 -->

       <!-- Slide 03 -->
       <div class="contents">
         <!-- Slide content goes here -->
       </div>
       <!-- End Of Slide 03 -->

       <!-- Slide 04 -->
       <div class="contents">
         <!-- Slide content goes here -->
       </div>
       <!-- End Of Slide 04 -->
     </div>
     <!-- End Of Inner Content parent -->
   </div>
   <!-- End Of Slider Parent -->
   ```

4. Customize the content of each slide as per your requirement.

## Customization

You can customize the appearance of the slider component by modifying the CSS in the `style.css` file. Here are some key customization options:

- Adjusting the dimensions of the slider:

  ```css
  .slider {
    width: 350px;
    height: 400px;
  }
  ```

- Changing the background color:

  ```css
  .slider {
    background-color: aliceblue;
  }
  ```

- Styling the navigation buttons:

  ```css
  .nav {
    /* Customize button styles here */
  }
  ```

- Modifying the slide content styles:
  ```css
  .contents {
    /* Customize slide content styles here */
  }
  ```

Feel free to explore and experiment with the CSS to achieve the desired look and feel for your slider component.

## License

This project is licensed under the [MIT License](LICENSE).
