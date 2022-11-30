# qr-code
# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)


## Overview
This challenge consists of building a QR code component and get it looking as close to the design attached as possible.


### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: https://soniaela.github.io/qr-code/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles


### What I learned

CSS Variables - Whilst not indispensable, I added all the colors provided by the style guide as a variable for practice purposes.

All the variables are added to the root to make them global. Since this is a small project, I did not think declaring variables with limited scope would be necessary. 

CSS 'local' variable example:
```css
#menu-items {
  --menu-color-blue: blue;
}
 
#menu-items a {
  color: var(--menu-color-blue);
}
```

CSS 'global variable example:
```css
:root {
  --orange-color: #FF933A;
}

body {
  background-color: var(--orange-color);
}
```


### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- https://dev.to/ljcdev/a-quick-hack-to-using-local-images-on-codepen-4cfp - Help in how to store images on codepen.io pens. 

