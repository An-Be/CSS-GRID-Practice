# CSS GRID Practice

This is a repository that holds my CSS Grid Practice. I want to make a clone of [AMEX website's homepage](https://www.americanexpress.com/). To complete it effectively, Jonathan my
coach over at Multiverse mentioned that I could incorporate CSS Grid and Flexbox. I currently already know flexbox but I have never used CSS Grid so I started doing some research.
## Table of contents

- [My process](#my-process)
  - [What I learned](#what-i-learned)
  - [Projects](#projects)
- [Author](#author)

## My process

I first started going over a few youtube videos and then to reinforce what I learned I completed Frontend Mentor's, Testimonials grid section project. You can find that in this github [repo](https://github.com/An-Be/Testimonials-grid-section-solution).
After that I still needed additional practice so I because I love games I have started playing ["Play Grid Attack"](https://codingfantasy.com/games/css-grid-attack/play) which is a website that helps you learn coding by playing games. Another website I found that will also help me in my learning is [CSS Garden](https://cssgridgarden.com/). CSS garden also helps you learn code by playing a game. Finally to reinforce what I have learned I found a few small projects that I am going to complete. Those projects can be found [here](https://www.freecodecamp.org/news/learn-css-grid-by-building-5-layouts/).

### What I learned

As of now I have learned the basics of CSS Grid. Like how to define a grid container, how to define the columns and rows, how to change the columns/row/position for individual children of a grid parent, and how to use grid-template-areas.

```css
.container{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: 1fr, 2fr, 1fr;
    gap: 10%;
}

```
```css
.container{
    display: grid;
    grid-template-areas: 
        'header header header'
        'nav content sidebar'
        'nav footer footer';
    grid-template-columns: 1fr 4fr 1fr;
    grid-template-rows: 80px 1fr 70px ;
}
header{
    grid-area: header;
}
nav{
    grid-area: nav;
}
main{
    grid-area: content;
}
sidebar{
    grid-area: sidebar;
}
footer{
    grid-area: footer;
}

```

### Projects

#### Testimonials grid section project

![](/images/Screenshot-large.png)

### Useful resources

- [Example resource 1](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Example resource 2](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
- [Example resource 3](https://www.w3schools.com/css/css_grid.asp)

## Author

- Website - [Andrea Berrocal](https://andreacodes-alpha.vercel.app/)