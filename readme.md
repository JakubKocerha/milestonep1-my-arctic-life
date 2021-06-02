# My Artic life

This project has two basic aspects: 
* __Experimental__
* __Environmental__

1. Experimental
- The site intends to find an alternative for people living in urban areas to spend their holidays or change their lifestyles. The focus is to make users experience a very simple or even primitive way of living in periods of life, compromise their comfort, and find a way to make them content about those choices. 

2. Environmental
- The right, meaningful and explanatory guidance should help the target group of people attain a stronger relationship to nature materially so crucial to their comfort zones wrapped in the city life. Their overall attitude should reach more understanding through participation and a careful approach to living in one of the last pristine natural environments left in Europe.

## Features

### Existing Features

- __Navigation Bar__
    - The navigation menu is identically featured on all four pages of the site.  It contains responsive links to all pages without reverting from any actual page to the home page.
    - [Hover effect](https://ianlunn.github.io/Hover/) ".hvr-radial-out" was used by inserting [external cdnjs library](https://cdnjs.com/libraries/hover.css/2.1.1) stylesheet in `<head>` element. The shade of green associates the main theme of the site.

![Nav bar](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/navbar.jpg)

- __The landing page image__
    - The main image is chosen to be the background of every page covering the whole viewport. The idea is subtle, with a dramatic arctic mountain landscape fading to the shades of black at the bottom of the page in color balance to the main heading My Arctic Life and abstract door opening with the subheading Leave The City Behind.

![Landing page](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/background-main.jpg)

- __Carousel section__
    - The Bootstrap-based carousel section contains a slideshow of few images related to the guide's life presented on the site.

![Carousel section](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/carousel.jpg) 

- __Footer__
    - The footer links users to relevant social media where they might potentially find more up-to-date information about the guide's life. The hover effect uses site-related green color background transition.  
    - The copyright text at the bottom of the footer is mainly to protect one of the photographers and her work provided solely for this site.

![Footer](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/footer.jpg)    

- __"Back to top" button__
    - The button is set on page Why Arctic?, Life and Join-me! and active only on resolution max 575px right between the main page section and footer. It is linked to the top of the current page and helps users avoid inconvenient UX scrolling. 

![Back to top button](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/back-to-top.jpg)

- __Why Arctic page__
    - Provides user understanding for guide's motives of his relocation to the far north. Those might be closely common for a target group of potential participants.

![Back to top button](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/why-arctic.jpg) 

- __Life page__
    - Gives users insights about possibilities and real-life example events and experiences in two major seasons: winter and summer. Bootstrap cards applied on the page have buttons with relevant external links. 

![Life-guide](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/life-guide.jpg)
![Life-winter](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/life-winter.jpg)
![Life-summer](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/life-summer.jpg)

- __Join-me page__
    - Provides form application to users interested in experiencing a short period stay in a remote uninhabited arctic area, learning new things and outdoor life respecting environment and diversity in nature.

![Join-me](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/join-me-to-arctic.jpg)


### Features To Implement

* More multimedia content(photos, videos, audio) from the life and the environment of site's presented guide.
* Guide's stories about critical moments and difficult conditions in the mountains(weather changes, injuries, broken equipment, etc.) and their solutions.
* Real action="#" link for collecting the posted data via form in join-me.html.

## Main technologies used
* HTML5
* CSS3
* [Bootstrap 4.2.1](https://getbootstrap.com/docs/4.2/getting-started/introduction/)
* [Github](https://github.com/)
* [Gitpod](https://www.gitpod.io/)
* [Pixlr](https://pixlr.com/)
* [Balsamiq](https://balsamiq.com/)
* [Cdnjs libraries](https://cdnjs.com/libraries/hover.css/2.1.1)
* [Font Awsome](https://fontawesome.com/)


## Testing

### Visual testing

* Google Devtools and its Toggle device toolbar with (responsive rule, grid blocks and given default mobile devices).
* Github deployed [My Arctic Life page](https://jakubkocerha.github.io/milestonep1-my-arctic-life/) on smartphone Samsung Galaxy Xcover Pro, laptop HP ProBook x360 11 G3 EE, and Dell screen res. 1920 x 1080px.
* Browsers used for testing - Google Chrome, Microsoft Edge.

### Form post/action link testing
* tested via [link](https://formdump.codeinstitute.net/) taken from CI Software develpment HTML tutorial.


### Validator testing
- HTML [W3C validator](https://validator.w3.org/) using URI of the site deployed to Github.
    1. [index.html W3C validator](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fjakubkocerha.github.io%2Fmilestonep1-my-arctic-life%2Findex.html)
        * No errors were returned.

    2. [why-arctic.html W3C validator](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fjakubkocerha.github.io%2Fmilestonep1-my-arctic-life%2Fwhy-arctic.html)
        * No errors were returned.
        * After recommendation of validator to review the alternative text to images, more accurate text added to [out-of-city.jpg](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/assets/images/out-of-city.jpg)
    
    3. [life.html W3C validator](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fjakubkocerha.github.io%2Fmilestonep1-my-arctic-life%2Flife.html)
        * Two stray Div end tags in markdown reported on line 225 and 226. Both deleted.

    4. [join-me.html W3C validator](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fjakubkocerha.github.io%2Fmilestonep1-my-arctic-life%2Fjoin-me.html)
        * Error 1 - __duplicate input ID__ - caused by incorrect modifying of Bootstrap form input markup. The second input ID and related label attribute changed from exampleFormControlInput1 into exampleFormControlInput2 in . A new ID was added to style.css for the rules styling the color of the text. The color of the placeholder text in the input fields was targeted with a new class .placeholder and styled in style.css.
        * Error 2 - __attribute value not allowed on element select at this point__ - caused inattentively and was deleted. The markup already contained attribute _name_ with _value_ **outdoor-experience**, which will be used for addressing the posted value of a selected option.

- CSS [W3C validator](https://jigsaw.w3.org/css-validator/)
    1. Validation of the site URI deployed on Github [My Arctic Life](https://jakubkocerha.github.io/milestonep1-my-arctic-life/)
        - 2 unsolved Errors related to Bootstrap libraries [(Jigsaw) validator URI](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjakubkocerha.github.io%2Fmilestonep1-my-arctic-life%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
           - Property _text-decoration-skip-ink_ doesn't exist : _none_
           - Property _backdrop-filter_ doesn't exist : _blur(10px)_

    2.  Validation - the direct input of [style.css](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/assets/css/style.css) with [(Jigsaw) validator direct input](https://jigsaw.w3.org/css-validator/#validate_by_input)   
        * No error found

### Google Developer Tools Lighthouse
Report from [PageSpeedInsight](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fjakubkocerha.github.io%2Fmilestonep1-my-arctic-life%2Findex.html).

### Responsive Design:
* Bootstrap grid applied in HTML markup
    * Extra small
    * Small
    * Large

* 5 media queries
    * The first media query layout and styling of content is for small devices like smartphones. It intended to make the layout of the content more appealing and easier to read from sizing, margin, paddings to the layout of the navbar, centering of text, and additional back-to-top button for quick navigation back to the menu of the site. 
    * The rest of the queries are focused on Bootstrap card bodies and their resizing to fit the text and stay leveled while changing the screen's resolution. None of the cards gets unevenly stretched beyond the rest of the cards while changing the resolution of the site with current content. 
    * Cards sequenced to block for extra-small devices, in the sequence of two cards in a row for small and medium devices, and four cards for large and bigger devices.
    * The site is mainly designed for smartphones, tablets, and laptops, and the content might appear visually small on screens with very high resolution. 
    


    
### Wireframes
- Links to wireframes below show the basic structure of each page on a mobile device, tablet, and laptop.

1. [Wireframe Home](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/page1-project1mainhome.png)
2. [Wireframe Why Arctic?](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/page2-projec1twhyarctic.png)
3. [Wireframe Life](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/page3-project1life.png)
4. [Wireframe Join-me](https://github.com/JakubKocerha/milestonep1-my-arctic-life/blob/master/readme-media/page4-project1joinme.png)

### Bugs and Debugging
#### Bugs
1. A commonly known bug with very low resolution, ca <200px, causes the float of the content to the left and creates a gap on the right side of the screen.
2. Homepage features on iPad Pro don't cover the whole height of the screen.

#### Debugging
1. Use of _"pointer-events: none;"_ targeting _.nohover_ class
    - Issue: when hovering over the label item with text "Email Address:", :hover rule got triggered above in the input for the label "Full Name:".
    The rule _"pointer-events: none;"_ solved the problem.
2. !important
    - Issue: default colors and box-shadows in buttons, inputs, dropdown menu, text-area.
    Overridden with !important.
3. Carousel
    - Issue: uneven slide between carousel images impacting the layout of bordering features caused by images of uneven sizes of images.
    Solved with default editing of images into the same size. 

## Deployment
### GitHub Pages
- The site was deployed to GitHub pages. The steps to deploy are as follows:
1. Log in to GitHub and locate the [GitHub Repository](https://github.com/JakubKocerha/milestonep1-my-arctic-life)
2. At the top of the Repository (not top of page), navigate to the _Settings_ button.
3. Scroll down the Settings page until you locate the _GitHub Pages_ Section.
4. Under _Source_, click the dropdown called _None_ and select _Master Branch_ and press _Save_. 
5. Once the _Master branch_ has been selected, the page will be automatically refreshed with a detailed ribbon including a link to the site to indicate the successful deployment. 

- The live link can be found here - https://jakubkocerha.github.io/milestonep1-my-arctic-life/
- The link to the repository can be found here - https://github.com/JakubKocerha/milestonep1-my-arctic-life

### Forking the GitHub Repository
- By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...
1. Log in to GitHub and locate the [GitHub Repository](https://github.com/JakubKocerha/milestonep1-my-arctic-life)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

## Credits
### Content
#### Fonts
- [Google Fonts](https://fonts.google.com/)
    * Font for the main heading _Mountains of Christmas_.
    * Font for the rest of the site _Lato_.
    * The fallback font _Sans Serif_.
#### HTML codes adopted from other sources:
[Bootstrap](https://getbootstrap.com/docs/4.2/getting-started/introduction/)
- Grid system
- Nav links
- Carousel
- Cards
- Form
- Footer

#### Pseudo-class effects:
- Nav links 
    - HTML code taken from [Code Institute tutorial](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/f99dac3afcfe4b2caf8d576273aea3e6/).
    - Overriding of Bootstrap, implementing and correct targeting of :active styling for Navlinks with the help of Code Institute tutor Fatima Aminu.
    
- Carousel
    - External Javascript links copied from [Bootstrap](https://getbootstrap.com/docs/4.2/getting-started/introduction/).

- Footer
    - HTML code and CSS styling taken from [Code Institute tutorial](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/b51f7b8b815c4bcd9979d2281b6d97a9/).
    - Footer icons taken from [Font Awsome](https://fontawesome.com/).

- Form, Buttons
    - styling and usage taken from [Stackoverflow](https://stackoverflow.com/questions/42134731/css-change-button-style-after-click), [W3S](https://www.w3schools.com/css/css_pseudo_classes.asp) and [Stackoverflow :focus class](https://stackoverflow.com/questions/42134731/css-change-button-style-after-click).

- Form label 
    - disabling of hover effect taken from [Stackoverflow](https://stackoverflow.com/questions/26754497/css-disable-hover-effect).
    

#### Others:
- Form 
    - Link for post method from Code Institute _The textarea Challenge_ to validate the functionality of the [Form](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+HE101+2020/courseware/fcc67a894619420399970ae84fc4802f/643317b091da4eef98fe9e0812a71715/).
    - Overriding colors and Bootstrap box-shadow with help of [Developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity).

- `<Meta>` elements
    - Meta and stylesheets copied from [Code Institute tutorial](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+HE101+2020/courseware/fcc67a894619420399970ae84fc4802f/59591be08b13436ebe782f57967be07a/).

- Button
    - Positioning of card buttons implemented with help of [Stackoverflow](https://stackoverflow.com/questions/48406628/bootstrap-align-button-to-the-bottom-of-card).

### Media
#### Textual content
1. Footer copyright
    - taken from [Love2dev.com](https://love2dev.com/blog/html-website-copyright/).
2. Other textual content - Jakub Kocerha.
3. Readme.md - some content for writting readme.md file was taken from [Code Institute README.md samples](https://github.com/Code-Institute-Solutions/SampleREADME) and [Code Institute readme-tepmlate](https://github.com/Code-Institute-Solutions/readme-template).

#### External links
##### Find out more! buttons
- [en.wikipedia.org](https://en.wikipedia.org/wiki/Ice_fishing)
- [sightsbetterseen.com](https://sightsbetterseen.com/abisko-sweden/)
- [www.deviantart.com](https://www.deviantart.com/tag/abisko)
- [en.wikipedia.org](https://en.wikipedia.org/wiki/Barbecue_grill)
- [www.swedenfishing.com](http://www.swedenfishing.com/en/articles/species_and_fishing_north_sweden)
- [visitsweden.com](https://visitsweden.com/what-to-do/nature-outdoors/hiking/top-hiking-routes-sweden/)
- [naturetravels.wordpress.com](https://naturetravels.wordpress.com/2007/11/20/mosquitoes-in-sweden-fact-and-fiction/)
- [www.scandinaviastandard.com](https://www.scandinaviastandard.com/a-guide-to-swedish-berries/#:~:text=A%20member%20of%20the%20rose,a%20wine%2Dlike%20flavor%20profile.)

##### Social media
- [Youtube](https://www.youtube.com/)
- [Facebook](https://www.facebook.com/)
- [Twitter](https://twitter.com/)

#### Images
- All used photos except those specified below were taken by Jakub Kocerha and Tuva Holmquist, who has given consent to use their images solely for this website.

- Photo for the card _Childhood dream_ downloaded and edited from Open source site pexels.com [Author Stein Egil Liland](https://www.pexels.com/photo/aurora-borealis-1933239/).
- Photo for the card _Adventure_ downloaded and edited from Open source site pexels.com [Author Spencer Gurley](https://www.pexels.com/photo/photo-of-person-on-kayak-1497585/).
- Photo for the card _Never forget_ downloaded and edited from Open source site pexels.com [Author Pavel Hajek](https://www.pexels.com/photo/a-mosquito-on-green-leaf-in-close-up-photography-4056767/).
- Photo for the Form container background downloaded and edited from Open source site pexels.com [Author Gantas Vaičiulėnas](https://www.pexels.com/photo/hands-over-a-bonfire-4323761/).


