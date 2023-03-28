# 02 Portfolio Project

## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |   
| Git | [https://git-scm.com/](https://git-scm.com/)     |    

<hr/>

## Description 

[Visit the Deployed Site](https://jeppjeppjepp0.github.io/html-git-css-challenge/)

This challenge's goal is to create a website using HTML and CSS to diplay past coding projects and associated images for potential employers. This project focused heavily on the use of flexbox and other advanced CSS concepts. The specific criteria are given below.

```md
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

<hr/>

## Table of Contents

* [CSS Flexbox Example](#css-flexbox-example)
* [Learning Points](#learning-points)
* [Author Info](#author-info)

<hr/>

## CSS Flexbox Example

The most commonly used concept for this project was the flexbox to order on-screen content. Everything displayed on the site except for the h1 title is controlled with the flex function of CSS. The clearest use of the flex display were the cards in the projects section of the page (as seen below). The below commands determine where and how the cards are displayed on the website, though the coloring and decorations are defined in other sections of the stylesheet.

```css
.card-container {
    display: flex;
    background-color: var(--dark);
    flex-wrap: wrap;
    justify-content: center;
    align-content: center;
}
```

<hr/>

## Learning Points 

The flex container and the way it controls the display was the most important concept used in this project (seen in almost every aspect of the page's design).

The second most used concept would be box-diagram work as well as border styling. These concepts were used in the diplay of the card class as well as the margins and padding of every other section. 

<hr/>

## Author Info

```md
### Jedd Javier


* [Portfolio](N/A)
* [LinkedIn](https://www.linkedin.com/in/jedd-javier-4b323426b/)
* [Github](github.com/jeppjeppjepp0)
```