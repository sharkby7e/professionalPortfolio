# professionalPortfolio

## Description 

The goal of this project is to create a responsive and informative portfolio page in order to showcase previously completed web applications. The webpage had certain specifications that needed to be met, which inclded the following points:

* [A responsive mobile first layout](#responsive-layout)
* [A portfolio of previous work](#portfolio)

## Link and preview of the site. 

[Click to view the website](https://sharkby7e.github.io/professionalPortfolio/)

![A gif of the website functioning](./assets/img/professionalPortfolio.gif)

## Key features of application

### Responsive Layout
To have this site look nice on mobile, I wanted the navbar to be on the bottom. On larger screens, I moved it to the left side of the page, which means I had to change the flex direction from column to row, in addition to resizing it. I also had to make sure that the link text remained hidden, which required a little refactoring  

```css
@media only screen and (max-width: 600px){
  .navbar{
    bottom: 0;
    width: 100vw;
    height: 5rem;
    margin: 0;
  }
  .menu {
    flex-direction: row;
```


### Portfolio
I used the Materialize Framework for this feature, specifically the carousel. The carousel was implemented in the HTML, but in order to format it and choose options, I had to grab it using jquery. Materialize had great documentation that made the implementation of this element really easy. 

```javascript
$(document).ready(function(){
  $('.carousel').carousel({
    fullWidth: true,
    indicators: true
  });
});

```

## Summary
I have definitely improved in my skills since making my last portfolio. I have a much better grasp of using 3rd party frameworks to make layout and formatting easier. I enjoyed spending time picking a nice color palette, as well as making the page look clean and crisp. 
