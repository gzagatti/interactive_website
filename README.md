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

