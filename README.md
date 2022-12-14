# personal-portfolio
Live code: https://plywoodpallet.github.io/personal-portfolio/

## Features
- Fully responsive site for mobile, tablet and desktop viewing
- Art direction: Hero image becomes cropped on mobile sites

## TODO

- Mobile media query - since mobile layout was developed first, properties in main CSS file are actually mobile definitions. Move these into mobile media query for clarity (Find the properties overwritten by desktop query)
- use clamp() on hero text size, have a min fixed text size
- use clamp() on left/right padding size? 

## Project Notes
- Try designing the mobile site first
- How to float text over image. Set container div to position: relative, set image selector to position: absolute https://www.geeksforgeeks.org/how-to-place-text-on-image-using-html-and-css/
- How to center a position:absolute element. Didn't need to specify width as recommended. https://stackoverflow.com/questions/8508275/how-to-center-a-position-absolute-element
- Resizing an image to always fit in browser window uses CSS grid https://stackoverflow.com/questions/6169666/how-to-resize-an-image-to-fit-in-the-browser-window
- Responsive text using viewport units. Used to using vw/vh to set sizes of containers, didn't know it could be used for text https://www.w3schools.com/howto/howto_css_responsive_text.asp
- for some reason the semantic tags (<article>) don't like being styled. I have to make a div within it in order to style content within
- site responsive function can be as simple as turning flex or grid on and off (large screen: turn on flex to fill content horizontally. small screen: turn off flex and have natural block display take over, place elements vertically on new lines)
- First usage of art direction. Hero image becomes a smaller, cropped version for mobile
- Page responsive without tablet breakpoint 
- Does reducing code in each media query definition increase performance? Or does the existence of media queries reduce performance by a such a large fixed amount that performance gains by reduction (ex clamp, minmax, etc) are not work doing?