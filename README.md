# CSS-Animated-Glowing-Gradient-Border-Effects
CSS Animated Glowing Gradient Border Effects

 Overview

This repository contains a set of CSS code that creates an animated glowing gradient border effect using the provided HTML structure. The primary purpose of this code is to showcase a visually appealing design with rotating gradients and a glowing border.



Installation

You can use the provided code by either downloading the repository or including the relevant HTML and CSS directly into your project.

1. **Download Repository:**
   - Download the repository as a ZIP file.
   - Extract the contents to your project directory.

2. **Include Code:**
   - Copy the HTML structure and CSS styles from [index.html](index.html) and [styles.css](styles.css) files, respectively.
   - Paste the code into your HTML and CSS files.

## Usage

To integrate the animated glowing gradient border effect into your project, follow these steps:

1. Include the CSS file in your HTML document:

    ```html
    <link rel="stylesheet" href="path/to/styles.css">
    ```

2. Use the provided HTML structure within the body of your HTML document:

    ```html
    <div class="box">
        <span></span>
        <div class="box">
            <span></span>
        </div>
    </div>
    ```

 Customization

You can customize the appearance of the glowing gradient border effect by modifying the CSS variables in the [styles.css](styles.css) file. Here are the main variables you can adjust:

- `--border-width`: Adjust the width of the border.
- `--a`: Control the rotation angle of the gradients.
- Various other properties such as `width`, `height`, and `top` for `.box` and `.box .box` elements.

Feel free to experiment with these variables to achieve the desired visual effect.

```css
:root {
    --border-width: -5px;
    --a: 0deg;
}

.box {
    --border-width: var(--border-width);
}

/* ... other styles ... */
```


**Note:** The provided demo link is a placeholder and should be replaced with the actual URL if you decide to host your demo.
