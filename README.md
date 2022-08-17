# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview
  Setting up the github repository for the project, I headed up to create the mobile version of the page first. Once I completed the mobile version, I started teh desktop version, but was confused regarding adding a different image using media-query. After some googling I figured a way out.

### Screenshot
Desktop View

![](./Images/Screenshot%20from%202022-08-17%2008-01-33.png)


Mobile View

![](./Images/Screenshot%20from%202022-08-17%2008-03-52.png)

### Links

- Solution URL: (https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa/hub/        product-preview-card-component-1sOtwVprNz)
- Live Site URL: (https://abdulhasibn.github.io/Product_preiview_card_component/)

## My process
  I started with mobile-first approach. Initially I setup the things needed for the page, like fonts and attaching the stylesheet. Once that is done, I structured the page using HTML. It is not written in a semantic format though. Then proceeded to add styles to the page in css for the mobile view. When I started to build the desktop view, the problem of changing the images according to the device's width came up. When I read some answers on stackoverflow, I found that it can be achieved by adding both the images to HTMl and then adjusting the image's display using media query. 

### Built with

- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Using media query to  toggle between the images according to the device's width is new to me. Through this challenge I got a good grasp of that concept.

### Continued development

The more I develope pages and see others talking about them, I get to understand the importance of semantic HTML more. Need to learn it and understand it better.

### Useful resources

- (https://stackoverflow.com/questions/12776434/media-query-image-src-property-change-using-css#:~:text=Use%20a%20sprite%20sheet%20and%20alter%20the%20background-position,depending%20on%20your%20media%20query%20criteria.%20Example%3A%20HTML%3A) - This question from stackoverflow helped to understand the toggling between images upon device width better.

## Author

- Frontend Mentor - [@abdulhasibn](https://www.frontendmentor.io/profile/abdulhasibn)
- Twitter - [@abdulhasibn](https://twitter.com/abdulhasibn99)
