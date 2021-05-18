
Notes needed to be rewritten in markdown

Credit
1. to CI tutorials for <head> coding(mostly meta and stylesheets, copied from a tutorial)
2. JavaScript codes for Bootstrap 4.2.1 copied from https://getbootstrap.com/
3. Google fonts
4. www.exels.com for photos


Debugging
1. Issue with displaying inline-block navbar items in bootstrap small resolution(<576px) solved by setting style inside media query for max-width:576px for div wrapping nav ul in position:relative;  and nav ul position: absolute; display:block;
2. Solve the issue with an overflow of slideshow over absolutly positioned nav bar items small breakpoit. Fixed byt setting the top margin of the column wrapping the carousel slideshow. 
3. Instagram Fontawsome icon doesn't work. Problem solved by deleting the Instagram icon for now:)
4. Unstable positioning of elements when on very low screen resolution, what is considered as a very common issue. 
5. Cannot make .active class in nav bar working while using A collection of CSS3 powered hover effects
6. Having problems with layout. I made a mistake in the beginning by not setting the col class to li items. I mistakenly tried to solve with with the positioning and @media queries unless I realized that my coding going completely wrong direction. In a CI tutorial I found out about col class and remade my work. 
7. Having problem with jerky background while carousel sliding. I solved it with setting the default width and height of images before uploading them to Gitpod.
8. Jerking :hover especially on lower resolution at the element border area of nav links solved by positioning of nav li and nav a and setting widths in percentiles. 