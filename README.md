# Bazaar-Ceramics-Website
Building and testing responsive webpages with HTML and CSS

![alt text][index.html]

[index.html]: https://github.com/SD-Smith/Bazaar-Ceramics-Website/blob/master/index.jpg
"Bazaar Ceramics Home Page"

## Assessment Details

### Units: 
* ICTWEB505 Develop complex web page layouts
* ICTWEB506 Develop complex cascading style sheets

### Tasks:
1. Build web page layouts using HTML and CSS
2. Create navigation using HTML and CSS
3. Create a responsive design suit different devices
4. Ensure HTML and CSS are validated and tested in all major browsers
5. Ensure website is accessible

### Constraints:
* __HTML__ - index.html, company_bg.html (background), and company_mission.html
* __CSS__ - style.css, laptop.css, tablet.css, mobile.css
* Autumn Color Scheme
* No placeholder images or text

### Assumptions:
* No SASS / SCSS
* No Javascript

## My Process
![alt text][prototypes]

[prototypes]: https://github.com/SD-Smith/Bazaar-Ceramics-Website/blob/master/prototypes.jpg
"late stage prototypes drawn in Adobe XD"

### Cross Browser Compatibility (Task 4)
The following desktop web browsers were at my disposal during design and testing.

__modern browsers:__
* Chrome
* Firefox
* Opera
* Edge

__older desktop browsers:__
* IE 11
* Safari 5 (windows version)

__andriod browsers:__
* Chrome for Android
* Samsung Internet Browser

_In addition, the device emulation tools provided by Chrome, Edge and Firefox have been used._ 

### Applying CSS styling through Progressive Enhancement (work in progress..)

Browsers with...

|least support | some support | full support |
|--------------|--------------|--------------|
| inline-block |   position   |              |
| float        |   flex       |   grid       |
| table        |   @media     |   @supports  |
|   | background-image |    |


1. A single column webpage layout using display: block and float: left/right
2. A responsive layout for mobile, tablet and laptop screens using flexbox and CSS media queries  
3. Responsive multi-column layouts using CSS grid and CSS feature queries
