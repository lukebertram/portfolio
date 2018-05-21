# Portfolio: Beyond the Basics

#### A responsive portfolio page utilizing Sass, Flexbox, and CSS transitions. December 15, 2017

#### By **Luke Bertram**

## Description

This is either a landing page for my multi-page portfolio website or the initial draft of a multi-part, modal, single-page site to serve the same purpose.

## Setup/Installation Requirements

For greatest ease of use, simply visit [this website](http://lukebertram.github.io/portfolio) in your web browser of choice. However, if you're feeling frisky, you can also use the following steps to clone the project from [GitHub](http://github.com) and run it locally on your own computer:

 * Visit the github page for [this project](http://github.com/lukebertram/portfolio)
 * Click the "Clone or Download" button and copy the address found there. Alternatively, just copy this address to your clipboard: https://github.com/lukebertram/portfolio.git
 * Access your system's command line interface (_ie Terminal, for MacOS Users_) and navigate to your home directory by entering the following magical spell into your command line (note: do not enter the '$' character):
 >$cd ~

 * Next, cast the following, more advanced spell:  
 >$git clone https://github.com/lukebertram/portfolio.git

 * Finally, open the project in your system's default web browser with the following final incantation:
 >$open portfolio/index.html


## Known Bugs

The font size of the biography or 'main' section is still a bit wonky, and feels way too big at larger screen sizes.

Also, the gallery items are not yet links to the associated projects. The hover transition for information is also not currently usable on a mobile device - as one must click on the item to focus it and see the information. Perhaps there is a way to set up a different functionality for touch devices wherein a first click will reveal the project information, and a second click will activate the link.

## Support and Contact Details

Flag me down in class, or send me a tweetbook on facestagram if you have any troubles.



## Research

The responsiveness of my website seems like it's going to be pretty dependent on the responsiveness of the various pieces of large text involved. I have heard tales of the "relative em" unit of measurement and intend to determine whether it can be used to accomplish my goals.

update: nope. No time to find out how to do it right before the 5:00pm deadline. Someday I will learn.

## Technologies Used

This project uses SASS to efficiently generate the final CSS stylesheet for the webpage. The CSS styling makes use of flexbox to position elements around the page and transitions/animations to add a bit of life to interactable elements.

If you would like to work on the styling of this site, I recommend using the following command to set a SASS watch that will detect changes to your SCSS files and automatically re-compile them into CSS:

`$ sass --watch scss:css`

### License

MIT License

Copyright (c) 2017 **Luke Bertram**
