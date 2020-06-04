# Project 0

Web Programming with Python and JavaScript

All pages should contain the Project number, Website title and a navigation bar.
The navigation bar use icons from an Icon library and allows user to navigate to all the website pages.

Used Sass file master.scss to generate a stylesheet master.css
SCSS inheritance is used with font and makes it easy to change font for different elements.
and the @media changes the font for small screens.
Variables define the colors used to style the website making it easy to change the website look.

index.html
Content: CV information.

I first worked on it with 2 sections but then I learned about bootstrap grid!
Problem solved.  So on this page I use the boostrap grid with 2 colums and 2 tables
Includes an image and a link to world.html
Integrated Boostrap progress-bar element.
Took the idea of the look of this page from https://www.w3schools.com/w3css/tryw3css_templates_cv.html as a base to start working.


world.html
Content: About Costa Rica the country were I live.

It has a boostrap 2 colum grid and a flexbox class container with wrap for the
pictures.  I tried to style the images on the css file using flex-container > img
but it did not work so I ended using a % that I can change with the style definition.
Contains a link to an external webpage that opens in another window.

family.html
Content: About my family

Same format that world html.  Contains 2 unordered lists that are formated using the SASS nesting.

activity.html
Content:  Activities I like to do.

Same format only it uses 4 column grid.   The flexbox container for pictures is not within any column.
Columns have an Id so that I can control the background color in accordance to the color variables defined in the SCSS file.
