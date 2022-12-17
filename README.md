# personal-portfolio
Live code: https://plywoodpallet.github.io/personal-portfolio/

## TODO
- replace header background with a polygon instead of background-color
- Choose some custom fonts. A Serif font for titles and headings, a sans serif font for descriptions. Set font sizes so it looks good on mobile
- Make another media query for desktop sites
-- load larger images if necessary
-- increase font sizes
-- tricky change in header/about-me layout

## Project Notes
- Try designing the mobile site first
- How to float text over image. Set container div to position: relative, set image selector to position: absolute https://www.geeksforgeeks.org/how-to-place-text-on-image-using-html-and-css/
- How to center a position:absolute element. Didn't need to specify width as recommended. https://stackoverflow.com/questions/8508275/how-to-center-a-position-absolute-element
- Resizing an image to always fit in browser window uses CSS grid https://stackoverflow.com/questions/6169666/how-to-resize-an-image-to-fit-in-the-browser-window
- Responsive text using viewport units. Used to using vw/vh to set sizes of containers, didn't know it could be used for text https://www.w3schools.com/howto/howto_css_responsive_text.asp
- for some reason the semantic tags (<article>) don't like being styled. I have to make a div within it in order to style content within