## Starfox Galaxies Travel
========

### Objective

Create a responsive layout for the 


### Requirements

- **Foundation**
 	- Use **Foundation** as the client-side framework for this layout project. 
	- Use the Foundation components that are necessary to complete the project. **Do not import all the components.**
- **Sass**
	- Use **Sass** for your css preprocessor.
	- Practice using **inline media queries**
	- Practice using **nested styles**
	- Practice using **variables**	
	- Practice using **mix-ins**
	- Because the project uses foundation, you do not need to include your own CSS Reset or Clearfix styles.
- **Layout**
	- The mobile layout requires a **dropdown nav**.
		- **Easy Mode**: Use a custom nav for medium and large sizes and a foundation top-bar for small sizes. Hide the nav you don't need at the appropriate size.
		- **Hard Mode**: Use only the foundation top-bar for the nav. You will have to override the foundation styles with your own custom styles for both small large layouts.
	- **Media Query Ranges**: The layouts included show small, medium, and large sizes. Set the media ranges for the project **as you see fit**. Use Foundation's conventions for setting media query ranges.
- **Server**
	- Use **LiveReload**.
	- Utilize **gulp** for your task runner (runs the server, gulp, gulp-sass, and livereload).
	- Instructions for **gulp+sass+livereload** setup are [here](https://gist.github.com/theRemix/b9f10de0bead6a7eaf5a)
	- Be sure that your bower components and node modules are listed in the **.gitignore** file.

### File Structure 
After you finish setting up your environment, your file structure should look like this:

``` 
.bowerrc
.gitignore
bower.js
gulpfile.js
package.json
/layouts
	/assets
/node_modules
/public
	/css
		styles.css
	/bower_components
	/images
	index.html
/sass
	styles.scss
	/partials
		_foundation.scss
		_settings.scss
		(more partials here if needed)

```

### Process

1. Whiteboard the layout at all sizes, from the most complex layout to the least complex layout and label the structure with appropriate **Foundation** classes, and add in your own classes and divs where appropriate.
	- mark divs with appropriate **.rows** and **.columns**
	- mark divs with **hide-for-** and **show-for-** classes
	- if there are any sibling **.row** items, it is a good idea to wrap them in a div with an your own identifying class.
2. Write the HTML markup for the layout using the most complex layout as a reference.
3. Ask an instructor to check your markup.
4. Style the layout mobile-first, in this (suggested) order:
	- set base styles (base font size, general font, etc)
	- fine-tune your structural components/layout (widths, columns, padding, and margin)
	- typography
	- any other elements and details
	

==========


The purpose of this exercise is to increase proficiency in web ui layout creation with focus on best practices*, cross-browser compatibility, accuracy, and speed (in this order).  

*best practices in this exercise is defined as "all common, current, and modern best practices in respect to semantic html5 markup[[1]](http://diveintohtml5.info/semantics.html)[[2]](http://html5doctor.com/lets-talk-about-semantics/)[[3]](http://coding.smashingmagazine.com/2011/11/18/html5-semantics/), [validated html](http://validator.w3.org/), [validated css](http://jigsaw.w3.org/css-validator/), and clean javascript[[1]](http://www.thinkful.com/learn/javascript-best-practices-1/)[[2]](http://code.tutsplus.com/tutorials/24-javascript-best-practices-for-beginners--net-5399)[[3]](http://www.thinkful.com/learn/javascript-best-practices-1/)."