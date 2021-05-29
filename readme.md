# My Artic life

This project has two basic aspects: 
* __Experimental__
* __Environmental__

1. Experimental
- The site intends to find an alternative for people living in urban areas to spend their holidays or change their lifestyles. The focus is to make them experience a very simple or even primitive way of living in periods of a lifetime, compromise their comfort, and find a way to make them content about those choices. 

2. Environmental
- The right, meaningful and explanatory guidance should help the target group of people attain a stronger relationship to nature materially so crucial to their comfort zones wrapped in the city life. Their overall attitude should reach more understanding through participation and a careful approach to living in one of the last pristine natural environments left in Europe.

## Features

### Existing Features

- __Navigation Bar__
    - The navigation menu is identically featured on all four pages of the site.  It contains responsive links to all of the pages without reverting from any actual page to the home page. 
    - [Hover effect](https://ianlunn.github.io/Hover/) .hvr-radial-out" was used by inserting [external cdnjs library](https://cdnjs.com/libraries/hover.css/2.1.1) stylesheet in `<head>` element. The shade of green associates the main theme of the site.

![Nav bar](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/navbar.jpg)

- __The landing page image__
    - The main image is chosen to be the background of every page covering the whole viewport. The idea is subtle, with a dramatic arctic mountain landscape fading to the shades of black at the bottom of the page in color balance to the main heading My Arctic Life and abstract door opening with the subheading Leave The City Behind.

![Landing page](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/background-main.jpg)

- __Carousel section__
    - The Bootstrap based carousel section contains a slideshow of few images related to the guide's life presented on the site.

![Carousel section](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/carousel.jpg) 

- __Footer__
    - The footer links users to relevant social media where they might potentially find more up-to-date information about the guide's life. The hover effect uses site-related green color background transition.  
    - The copyright text at the bottom of the footer is mainly to protect one of the photographers and her work provided solely for this site.

![Footer](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/footer.jpg)    

- __"Back to top" button__
    - The button is set on page Why Arctic?, Life and Join-me! and active only on resolution max 575px right between the main page section and footer. It is linked to the top of the current page and helps users avoid inconvenient UX scrolling. 

![Back to top button](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/back-to-top.jpg)

- __Why Arctic page__
    - Provides user understanding for guide's motives of relocation to the far north. Those might be closely common for a target group of potential participants.

![Back to top button](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/why-arctic.jpg) 

- __Life page__
    - Gives users insights about possibilities and real-life example events and experiences in two major seasons: winter and summer. Bootstrap cards applied on the page have buttons with relevant external links. 

![Life-guide](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/life-guide.jpg)
![Life-winter](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/life-winter.jpg)
![Life-summer](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/life-summer.jpg)

- __Join-me page__
    - Provides form application to users interested in experiencing a short period stay in a remote uninhabited arctic area, learning new things and outdoor life respecting environment and diversity in nature.

![Join-me](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/join-me-to-arctic.jpg)


### Features to implement

* More multimedia content(photos, videos, audio) from life and environment of presented guide.
* Guide's stories about critical moments and difficult conditions in the mountains(weather change, injuries, broken equipment, etc.) and their solutions.
* Real action="#" link for collecting the posted data via form in join-me.html


## Testing
### Visual testing
* Google Devtools and its Toggle device toolbar with (responsive rule and grid blocks)
* Github deployed ![My Arctic Life page](https://jakubkocerha.github.io/milestonep1-my-arctic-life/) on smartphone Samsung Galaxy Xcover Pro, laptop HP ProBook x360 11 G3 EE and Dell screen res. 1920 x 1080px.

### Form post/action link testing
* tested via [link](https://formdump.codeinstitute.net/) found in CI Software develpment HTML tutorial.


### Validator testing
- HTML [W3C validator](https://validator.w3.org/)
    1. [index.html W3C validator](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fjakubkocerha.github.io%2Fmilestonep1-my-arctic-life%2Findex.html)
        * No errors were returned when passing through the official. 
        * Recommendation of validator to implement h2-h6 heading ignored for the intent of design to implement only carousel slideshow with photo content in the main section.

    2. [why-arctic.html W3C validator](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fjakubkocerha.github.io%2Fmilestonep1-my-arctic-life%2Fwhy-arctic.html)
        * No errors were returned when passing through the official.
        * After recommendation of validator to review the alternative text to images, more accurate text added to [out-of-city.jpg](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/assets/images/out-of-city.jpg)
    
    3. [life.html W3C validator](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fjakubkocerha.github.io%2Fmilestonep1-my-arctic-life%2Flife.html)
        * Two stray Div end tags in markdown reported on line 225 and 226. Both deleted.
        * Recommended structural outline of headings - h3 child of a div with class .life-image changed in `<p>` element with similar styling of the text to fit the original intent of the design. 

    4. [join-me.html W3C validator](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fjakubkocerha.github.io%2Fmilestonep1-my-arctic-life%2Fjoin-me.html)
        * Error 1 - __duplicate input ID__ - caused by incorrect customizing Bootstrap form inputs markup. The second input ID and related label atribute changed from exampleFormControlInput1 into exampleFormControlInput2 in . New ID was added to style.css for the rules styling the color of the text. The color of the placeholder text in the input fields was targeted with a new class .placeholder and styled in style.css.
        * Error 2 - __attribute value not allowed on element select at this point__ - caused inattentively and was deleted. The markup already contained attribute _name_ with _value_ **outdoor-experience** which will be used for addressing the posted value of a selected option.

- CSS
  - Errors [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjakubkocerha.github.io%2Fmilestonep1-my-arctic-life%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
        
*
*
*
*
*
*
*
Fill it up
*
*
*
*



### Wireframes
- Links to wireframes bellow show the basic structure of each page on mobile device, tablet and laptop.
### Responsive design:
* Bootstrap grid
    * Extra small
    * Small
    * Large

* 5 media queries
    * The first media query layout and styling of content is for small devices like smartphones. It's intent was to make the layout of the content more appealing and easier to read from sizing, margin, paddings to layout of navbar, centering of text and additional back-to-top button for quicker navigation back to menu of the site. 
    * The rest of the queries is focused on Bootstrap card bodies and their resizing to fit the text and stay leveled while changing the the resolution of the screen. None of the cards gets unevenly stretched  beyond the rest of the cards while changing the resolution of the site with current content. 
    * The site is designed mainly for smartphones, tablets and laptops and the content might appear visualy small on screen with very high resolution. 
    


1. [Wireframe Home](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/page1-project1mainhome.png)
2. [Wireframe Why Arctic?](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/page2-projec1twhyarctic.png)
3. [Wireframe Life](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/page3-project1life.png)
4. [Wireframe Join-me](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/page4-project1joinme.png)