# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)

## Overview

### Screenshot

![](./screenshot.png)

### Links

-   Solution URL: [URL here]()
-   Live Site URL: [URL here]()

## My process

### Built with

-   CSS custom properties
-   Flexbox
-   Positioning

### What I learned

-   combine background-image and background-color :

```css
body {
    background-image: url("images/pattern-background-desktop.svg");
    background-repeat: no-repeat;
    background-color: hsl(225, 100%, 94%);
    background-size: cover;
}
```

-   set up code for css file

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

p {
    font-size: 16px;
}

img {
    max-width: 100%;
}

body {
    min-height: 100vh;
    background-color: var(--pale-blue);
    font-family: Red Hat Display, serif;
}
```

-   border-radius for image inside a div

```css
.container {
    overflow: hidden;
}
```

### Continued development

-   Semantic HTML5 markup

### Useful resources

-   ...
