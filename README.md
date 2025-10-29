# Accessibility Design Co.

## 🌐 Live Site
**[adco.com](https://magali-la.github.io/accessible-design-co/)**

## Project Overview
This project was created as part of an assignment with Per Scholas. It features:

* A responsive nav and footer component
* Responsive grid and flex layouts
* Overrides of default browser focus indicators for heightened visibility
* Simple media query breakpoints for mobile sizes under 700px

## Process
* Comprehensive plan for features
* Collected assets - illustrations from Streamline (New York Set on Figma) 
* Created assets - Logo
* Researched accessible Google Fonts
* Worked section by section for content
* Then went into responsive elements for sections that required it
* Added ARIA labels
* Added focus elements in the end for all links, input and buttons

## How to Test
* Go to the live link and click inspect
* Then test different responsiveness by dragging the screen size or clicking on the different breakpoints in dev tools
* Hover over buttons and links to check interactivity
* Try to submit the form without content, then submit with content
* Use tab to navigate through links, buttons, and input field, checking if the orange focus indicator is visible

## Reflections

### What accessibility challenges did you face, and how did you address them?
* The main challenge was using aria labels correctly for the accessibility tree
* I tested and some elements could be inclusive
* One challenge was getting the background image on the about section to be lighter to have enough contrast without modifying the image too much and losing its effect - I considered adding a text shadow behind the black text
### How did you ensure that your design was responsive and accessible to all users?
* I went to inspect while working to check that my grid and flex layouts were responsive, and used tab navigation to verify my focus indicators were overriding the browser defaults
### What tools or resources did you find most helpful during this project?
* The most helpful was a website on ARIA and best practices using labels showing examples and context
W3 contrast checker
* And the checker that allowed me to input rgb values since I had a few in my project
* **[ARIA Guide](https://www.aditus.io/aria/aria-label/
)**
* **[Contrast Checker](https://app.contrast-finder.org/result.html?foreground=rgb%28154%2C+58%2C+23%29&background=FFEED6&ratio=4.5&isBackgroundTested=false&algo=Rgb&lang=en
)**

