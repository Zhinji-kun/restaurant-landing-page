# Krusty Krab Restaurant Landing Page

Welcome to the **Krusty Krab Restaurant Landing Page**! This project is a fictional restaurant website designed to resemble the iconic Krusty Krab from the animated series *SpongeBob SquarePants*. The website has been carefully built to feature the restaurant’s menu, opening hours, and a visually appealing layout, complete with custom fonts and images.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Testing and Validation](#testing-and-validation)
- [Installation](#installation)
- [Credits](#credits)

## Overview
The purpose of this project is to create a clean, responsive, and visually engaging landing page for the **Krusty Krab Restaurant**. It features various sections like the menu, restaurant description, and contact information, designed to offer an enjoyable browsing experience. The project aims to demonstrate proficiency in web development using HTML, CSS, and custom assets.

## Features
- **Responsive Design**: The layout adapts to different screen sizes (desktop, tablet, mobile).
- **Custom Fonts**: The page uses a custom "Krabby Patty" font for a playful and unique look.
- **Sticky Navigation Bar**: Ensures easy navigation, even when scrolling.
- **Animated Menu**: Hover effects are applied to menu items for added interactivity.

## Technologies Used
- **HTML5**
- **CSS3**
- **Custom Fonts**: (Krabby Patty font)
- **Media Queries**: For responsive design

## File Structure
```bash
project-folder/
│
├── index.html      # Main HTML file
├── styles.css      # CSS file for styling the webpage
├── /images         # Folder containing all images for the project
└── /font           # Folder containing the custom font
```

## Testing and Validation
### HTML Validation
The HTML code was validated using the **Nu Html Checker** and some issues were identified:
- **Invalid Image Paths**: Spaces were found in image file names, which caused validation errors. Ensure all file names follow standard URL encoding rules (replace spaces with `%20` or use hyphens).
- **Unclosed Elements**: The `<ul>` tag was left unclosed, and the `<section>` tag was closed improperly. Fixing these errors ensures the webpage renders correctly across all browsers.
- **Headings Structure**: Warnings were raised about the misuse of multiple `<h1>` elements. To improve accessibility, it’s recommended to use `<h1>` only for the main page title.

### CSS Validation
The CSS file was validated using the **W3C CSS Validator**, and no errors were found. The document adheres to **CSS level 3 + SVG** standards.
You may display the following W3C badge on your website to indicate valid CSS:
```html
<p>
  <a href="http://jigsaw.w3.org/css-validator/check/referer">
    <img style="border:0;width:88px;height:31px"
         src="http://jigsaw.w3.org/css-validator/images/vcss"
         alt="Valid CSS!" />
  </a>
</p>
```

## Installation
To run this project locally:
1. Clone the repository to your machine:
   ```bash
   git clone https://github.com/yourusername/krusty-krab-landing-page.git
   ```
2. Open the `index.html` file in your browser.

## Credits
This project was created by Zhinji. It includes custom fonts and assets inspired by *SpongeBob SquarePants*
