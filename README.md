## Starfox Galaxies Travel

### Objective

Create a responsive webpage for the Starfox Galaxies Travel using the  layouts included for reference.

- No CSS frameworks
- You may use a css-reset
- Use CSS's Flex Box to help with layouting out your elements.
- You must use SASS (via SCSS)
- You may use the Gulp build tool to:
  - transpile your SASS into CSS
  - run your server
  - have "live-reload" functionality

### Specifications

**Media Query Break-points**
- small layout max-width: `600px`
- medium layout min-wdith `965px` and max-width `1099px`
- large min-width `1100px` and up

**Note for Large and up break-point: ** Content will no surpass being `1100px` wide but the "white-space" can continue to grow if the user expands their screen-width to a large value.

Use a blank anchor href for links as placeholders, for example: `<a href="#">Home</a>`

### Requirements

- must use **Flex Box**
- **Sass** (via SCSS)
  - Practice using `Mobile-First` design principle
	- Practice using **defining media queries**
	- Practice using **nested styles**
	- Practice using **variables**
	- Practice using **mix-ins**
- **Layout**
	- The mobile layout requires a **dropdown nav**.
		1. **Easy Mode**: Build the as seen in the `layouts/Small-wOpenNav.png` only without click functionality. You can add it later. Work on the other layouts. Do **Hard Mode** when you're done
		1. **Hard Mode**: Use javascript to make the mobile nav hide and show upon clicking the `menu_icon.svg` image in the nav.
- **Server**
	- Use **Browser-sync**.
	- Utilize **gulp** for your task runner (runs the server, gulp, gulp-sass, and browser-sync).
	- Instructions for **gulp+sass+livereload** setup are [here](https://gist.github.com/theRemix/b9f10de0bead6a7eaf5a)
	- Be sure that your bower components and node modules are listed in the **.gitignore** file.

### File Structure
After you finish setting up your environment, your file structure should look like this:

```
/layouts
  /assets *copy images to /public/assets directory*
/node_modules
/public
  /css
    styles.css *this file is generated via Gulp*
  /assets
  index.html
/sass
  styles.scss
.gitignore
gulpfile.js
package.json
```

### Process

1. Start with the Mobile layout. Build with only enough HTML elements and CSS to achieve that layout. **There should be no media-query css code at this point.**
  - set base styles (base font size, general font, etc)
  - typography
  - any other elements and details
  - use semantic naming for your elements. Make them **MEANINGFUL**. example: Navigation items are a list of links so I'd use an `ul` element then add a class called `nav-menu` to it. `ul` element contain `li` elements, so I will then add the class `nav-items` to each `li`.
1. Once you're done with the mobile layout, move onto the Medium layout. If more elements are needed Modify the HTML as needed. **add your medium media query break-points now, these will override your "Mobile styles" which you defined previously.
1. Once you're done with the Medium layout, repeat the step above with the Large layout.

**Commit your code often**. Finished building a section of UI? COMMIT!
