# personal-portfolio
Live code: https://plywoodpallet.github.io/personal-portfolio/

## TODO
- main grid is not rendering, maybe it is not necessary, or semantic tags cannot be styled at all
- once main grid is working, replace padding with gap
- replace header background with a polygon instead of background-color

## Project Notes
- Try designing the mobile site first
- How to float text over image. Set container div to position: relative, set image selector to position: absolute https://www.geeksforgeeks.org/how-to-place-text-on-image-using-html-and-css/
- How to center a position:absolute element. Didn't need to specify width as recommended. https://stackoverflow.com/questions/8508275/how-to-center-a-position-absolute-element
- Resizing an image to always fit in browser window uses CSS grid https://www.geeksforgeeks.org/how-to-place-text-on-image-using-html-and-css/
- Responsive text using viewport units. Used to using vw/vh to set sizes of containers, didn't know it could be used for text https://www.w3schools.com/howto/howto_css_responsive_text.asp
- for some reason the semantic tags (<article>) don't like being styled. I have to make a div within it in order to style content within