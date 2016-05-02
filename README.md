# Soup to Bits: Build an Interactive Website

A step-by-step on how to build an interactive website from [codeschool.com](https://www.codeschool.com/screencasts/build-an-interactive-website-part-1)

## Part I

### First Steps

-  Start with 3 files:
    -   `index.html`
    -   `main.css`
    -   `app.js`

### The Index

-   website will be divide into two sections: header and main
-   posts would go with an ordered list

### The CSS

-  normalize: we want to reset the default stylesheets in order to build our own style
-  good idea to use color meter to have a good reference for the colors which we want to use
-  define base styles
-  add classes to the html
-  CSS properties are laid out alphabetically; some people order attributes by design attributes
-  a lot of tweaking in order to get the effect that we want

### The List

-  classes should be used to logically structure the html document

## Part II

### Metadata to Each Story

-   an unordered list is added with relevant metadata
-   we add a specific class to each metadata item
-   we set the display to inline and add some margin
-   fonts can be added from Google fonts

### jQuery

-   we can use cdn to link jQuery and given the browser's cacheing capabilities it won't need to re-download just for your website
-   add code to the bottom of the page
-   we should reference js-* classes only to js file and do not reference it in the CSS
-   is-* style CSS classes are good to reference transitioned states

### Form Field for Adding New Stories

-   need to inspect the element to see why the width of the form exceeds that of the rest of the container; the answer lies in the box size
-   to hide the form we need to set the opacity and visibility options off as well as set the height to 0; otherwise there would an empty space on the page
-   we need to add js classes

## Part 3

### HTML Setup

-   we'll design a modal popup
-   the HTML markup is placed just after the content's subheader

### CSS

-   we use absolute positioning which places above the parent's container
-   `left: 50%`: from the left edge of the container move it 50% of the width; then translate 50% which will place you 25% in the center
-   making text display on the picture is playing with position absolute and relative
-   `position: fixed` will stick the overlay on all four corners of the browser
