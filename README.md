# Professional Portfolio


## User Story

```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```


## Acceptance Criteria

Here are the critical requirements necessary to develop a portfolio that satisfies a typical hiring manager’s needs:

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
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
## Link to deployed application

* https://



## Mock-Up

The following animation shows the web application's appearance and functionality:

![portfolio demo](/assets/images/website-mockup.gif)



Below is an overview of the changes made to meet the University of Birmingham acceptance criteria:

## HTML

* Extensively commented the index.html file to allow any prospective employers to easily understand the way i have structured my Portfolio site and the thought process behind certain decisions i have made

* Added a SEO optimised page title

* Added a meta description to improve SEO for the site

* Added an area for a logo SVG image which i can easily change in future should i wish

* Created 3 main navigation links in the top nav, and also added a side navigation that the user sees when the page first loads - which has SVG icons that link to my Github and LinkedIn profiles, as well as an icon that lets anybody reach me via email

* linked an external javascript file and created a simple function where the top navigation links would convert into a hamburger menu when the viewport was less than 1000px width, and would listen for clicks on the hamburger icon and display or hide the navigation links as needed

* The 3 Navigation links scroll down to their relevant section

* Used semantic html tags across the site to define the main sections, including a hero area that  visitor first lands on when the page loads, which contains Nav tags button tags, an about me section, a projects section and a footer. Additional divs were placed inside these sections as needed in order to have precise control of styling and positioning via CSS

* Added extensive comments to the HTML file

* Added screenshot images to each project card

* Added view live site and view repo links to each card

* Made each project card image clickable - takes user to the live deployed site

* Added alt text for all images

* Added indentation and spacing for improved readability






## CSS

* Extensively commented the style.css file to allow the client to easily understand changes that have been made and the thought process behind them

* CSS selectors and properties have been re-ordered and organized to follow the cascade and semantic structure.

* Used CSS variables to make global styling changes easier in future

* Top navigation styling - applied some javascript to replace the nav links with a hamburger menu when the viewport is less than 1000px width. Also applied flex properties to make this container responsive to viewport changes and to ensure an even gap between the logo and the nav links 


* Added flex properties to each section of the site, ensuring all the project cards are fully responsive when viewed on mobile or tablet devices

* added a box shadow to each project card to make them more impactful and visually appealing

*  Added a minimum width to the project cards so that the content will remain readable all the way down to a viewport of 300px width

* Manually adjusted margin and padding for each section of the page, all the way down to individual elements

* Extensive use of a media query to dramatiically change the layout of the page on mobile devices - includes removing the logo from the top nav, changing the nav to a hamburger menu, moving my headshot so it above the about me text, resizing the download cv button so it is larger and displayed below the about me content, and more

* using a media query and the content:url CSS property to swap out the large hero image for a smaller one that is aligned with the sizing of the other project images to enhance look and feel when viewed on mobile devices

## JavaScript

* Created variables for the hamburger and nav-list CSS ID's

* Created a toggleButton function that shows and hides the 3 top navigation links

* Created an event listener that listens for clicks to the hamburger button, which shows or hides the 3 top navigation links


## Future Features and functionality

In future i would like to revisit this portfolio and explore the following:

* A CSS grid layout for my projects

* A table in the about me section showcasing all the programming languages i am skilled in 

* An interactive background in the hero section, possibly using the three.js framework to render something both 3d and interactive in realtime 

* Incorporating the react framework 

## My Development Environment

* VScode
* Terminal
* Google Chrome
* MacOS Monterey 
* Git
* Github

## Languages used

* HTML
* CSS
* Javascript