# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

#### Desktop design

<img src=".images/desktop.png" alt="Desktop design"/>

#### Mobile design

<img src=".images/mobile.png" alt="Mobile design"/>

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

To build this project, it was necessary to study and understand how does hover functionality works, since when the mouse pointer hovers over the selected button, it must modify its design.


```css
.sedans__button:hover{
    background-color: hsl(31, 77%, 52%);
    border-color: hsl(0, 0%, 95%);
    color: hsl(0, 0%, 95%);
}
```

It was also necessary to understand how to adjust the spacing between lines.

```css
.card__subtitle{
    padding-top: 10%;
    color:hsla(0, 0%, 100%, 0.75);
    font-family: 'Lexend Deca', sans-serif;
    font-size: 15px;
    line-height: 30px;
}
```


### Continued development


In future projects, I want to implement the use of JavaScript and DOM to try to make the page more interactive.


### Useful resources

- https://www.w3schools.com/css/css3_buttons.asp - This site helped me a build the hover button.
- https://www.delftstack.com/pt/howto/css/css-line-spacing/#:~:text=Use%20a%20propriedade%20line%2Dheight,aumentar%C3%A1%20ou%20diminuir%C3%A1%20de%20acordo. - This site helped me with the line spacing in the paragraphs.



## Author

- Frontend Mentor - [@luizarilo](https://www.frontendmentor.io/profile/luizarilo)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luiz-arilo)

