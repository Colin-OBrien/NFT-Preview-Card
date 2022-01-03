This is my solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). 

# Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

# Overview

In order to improve my CSS and HTML skills, I am completing challenges on FrontEnd Mentor.  This was a challenge to recreate an NFT web-page.

## The Challenge:

I should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

## Screenshot:

Here is a screenshot of my solution:

<img src="images/screenshot_completed.png" alt="Screenshot" style="max-height: 600px; max-width: auto;"/>

# My Process:

I tried to think of the different components and wanted to perfect the positions and structure of each component before moving on to another.  I had to be consciously aware of which components might interact with other components and work to make sure they are aligned and not interfering with each other.  I like to put borders around each of my flexbox containers so I can easily follow them.

So, I first set the positioning of the main container, the main image and the different sub sections.  I then worked my way through the components that make up each section from the top down.  First setting my main image properly, next my item header and sub-text.  I then moved on to my timer and price since these had additional icons to go along with the text. And finally, I added the creation box on the bottom and aligned the icons there as well. 

Once everything was in the place as I expected I added all styling to the text, colors, and backgrounds.  To wrap up the project, I added a horiztonal line and added the hover-on effects for items that could be interacted with.


## Built With:

- HTML5
- CSS
- Flexbox

## What I Learned:

This was my first big project that I did entirely on my own.  I learned a lot about my personal workflow and also how to find solutions for issues I am having.  Often times I have a good idea but have difficulty finding out how to implement it.  Some items I really struggled with.

Finally finding a solution to my hover on effects for the image was a big challenge and something that took a long time to resolve.
I eventually stumbled across a solution to make the background the color I want and have it come in through opacity of the main image.
```
  .img-container span {
    background: hsl(178, 100%, 50%);
    bottom: 0;
    display: block;
    left: 0;
    opacity: 0;
    position: absolute;
    right: 0;
    top: 0;
    z-index: 1;
    border-radius: 10px;
  }

  .img-container span:hover  { 
    opacity: 0.5;
    border-radius: 10px;
 }
}
```

## Author

- [Colin O'Brien]
- Frontend Mentor - [@Colin-OBrien](https://www.frontendmentor.io/profile/Colin-OBrien)

