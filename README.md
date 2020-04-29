# Natours: Tour Landing page

Hi there, for a while I have been working with plain **CSS** so I decided to take a course on **SASS**. In [Udemy](udemy.com) I landed on this course _[Advanced CSS and Sass_](https://www.udemy.com/course/advanced-css-and-sass). In this course there are three projects base on the three primary layout styles: float, lex, and grids. 
For this project, the first layout syntax; float was used. But before diving into what was done in the project and the output, I will like to list the objectives and a brief introduction on the architecture, etc...

## File Architecture
This project was done using two languages **HTML** and **CSS**, but because of the advantages using **CSS** preprocessors, the instructor explained these advantages and **SASS** was used.
### SASS file structure
	

 - abstract
	 - functions.scss (this file was never used in this project)
	 - variables.scss
	 - mixins.scss
 - base
	 - base.scss
	 - utilities.scss
	 - typography.scss
	 - animations.scss
 - components
	- bg-video.scss
	- button.scss
	- cards.scss
	- composition.scss
	- features.scss
	- form.scss
	- popup.scss
	- stories.scss
- layout
	- footer.scss
	- grid.scss
	- header.scss
	- navigation.scss
- pages
	- home.scss

### Project Objectives

 - Learn how CSS works in the background
 - Learn **BEM** methodology
 - Learn the 7-1 **SASS** architecture structure
 - Create grid layouts
 - Create animations on hover
 - Create Components
 - Create background videos
 - Responsive images in HTML and CSS for faster page-loads
 - The NPM ecosystem: development workflows and building processes
 - Tons of modern CSS techniques to create stunning designs and effects
 - Advanced CSS animations with @keyframes, animation and transition


## Tours Project
### Overview
The Tours project is a simple landing page, as the first project of this course, I decided to take it very serious and pay every attention to detail.
### NPM packages

```json
"dependencies": {

"node-sass": "^4.13.1",

"postcss-cli": "^7.1.0"

},

"devDependencies": {

"autoprefixer": "^7.1.4",

"concat": "^1.0.3",

"npm-run-all": "^4.1.5"

}
```
    
### Global Setting
 - For the first part the global variables are set, box-sizing: border-box
 - The body is given a padding in rem;yes, why rem?... I asked myself this same question, and it was simply because with just a single change in the root em value the contents of the page will full adjust.
 - The rem is set to 62.5% *//1 rem = 10px; 10px/16px = 62.5%*
 - 

